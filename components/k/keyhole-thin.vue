<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="q7q71xkix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:keyhole-thin" /></template>
<style>
.q7q71xkix {
  fill: currentColor;
  d: path("M128 28a100 100 0 1 0 100 100A100.11 100.11 0 0 0 128 28m0 192a92 92 0 1 1 92-92a92.1 92.1 0 0 1-92 92m36-108a36 36 0 1 0-57 29.22l-14.66 33.17A4 4 0 0 0 96 180h64a4 4 0 0 0 3.66-5.61L149 141.22A36.15 36.15 0 0 0 164 112m-23.66 29.33L153.86 172h-51.72l13.52-30.67a4 4 0 0 0-1.66-5.07a28 28 0 1 1 28 0a4 4 0 0 0-1.66 5.07");
}

</style>
