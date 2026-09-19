<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iar5v5b5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:exercices-de-gainage" /></template>
<style>
.iar5v5b5d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m5.5 26.829l27.943-5.859m-4.247.89v10.416h7.126m2.716-8.03a4.355 4.355 0 1 1-1.787-8.524a4.355 4.355 0 0 1 1.787 8.525M5.5 32.372V26.83");
}

</style>
