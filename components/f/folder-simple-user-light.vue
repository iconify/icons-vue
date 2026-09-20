<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="uzb8uxbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:folder-simple-user-light" /></template>
<style>
.uzb8uxbsx {
  fill: currentColor;
  d: path("M211.28 199a30 30 0 1 0-38.56 0a38.1 38.1 0 0 0-18.52 23.5a6 6 0 0 0 4.26 7.34a6.3 6.3 0 0 0 1.54.2a6 6 0 0 0 5.8-4.46C168.86 214 179.63 206 192 206s23.14 8 26.2 19.54a6 6 0 0 0 11.6-3.08A38.1 38.1 0 0 0 211.28 199M192 158a18 18 0 1 1-18 18a18 18 0 0 1 18-18m38-70v32a6 6 0 0 1-12 0V88a2 2 0 0 0-2-2h-85.33a14 14 0 0 1-8.4-2.8L94.53 62.4a2 2 0 0 0-1.2-.4H40a2 2 0 0 0-2 2v136a2 2 0 0 0 2 2h80a6 6 0 0 1 0 12H40a14 14 0 0 1-14-14V64a14 14 0 0 1 14-14h53.33a14 14 0 0 1 8.4 2.8l27.74 20.8a2 2 0 0 0 1.2.4H216a14 14 0 0 1 14 14");
}

</style>
