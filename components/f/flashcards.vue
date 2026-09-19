<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="uhd4l6b7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:flashcards" /></template>
<style>
.uhd4l6b7a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.243 7.561h19.514a2.65 2.65 0 0 1 2.657 2.658v27.563a2.65 2.65 0 0 1-2.657 2.657H14.243a2.65 2.65 0 0 1-2.657-2.657V10.219a2.65 2.65 0 0 1 2.656-2.658m1.108 9.325h17.703M15.35 20.312h17.703M15.35 23.74h17.703M15.35 27.166h17.703M15.35 13.459h7.097M15.35 30.593h7.097M15.35 34.02h17.703m-21.468 3.716h24.83m-16.556 0v2.702m8.283-2.702v2.702m-16.573-3.6L5.592 14.524a2.65 2.65 0 0 1 1.878-3.255h0l4.1-1.099m24.861 26.668l5.977-22.314a2.65 2.65 0 0 0-1.878-3.255h0l-4.1-1.099");
}

</style>
