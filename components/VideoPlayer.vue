<template>
  <iframe
    with="560"
    height="315"
    :src="`https://player.vimeo.com/video/${props.videoId}`"
    title="Video Player"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
    allowfullscreen
  >
  </iframe>
</template>

<script setup>
const props = defineProps(["videoId"]);
</script>

<style scoped></style>
