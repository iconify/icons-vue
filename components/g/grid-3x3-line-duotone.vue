<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xvjk-cbox"/><path class="qg_0yybkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:grid-3x3-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qg_0yybkg {
  d: path("M8.69562 2.05956L8.69562 8.687M8.69562 8.687L8.69562 15.3132M8.69562 8.687L15.3219 8.687M8.69562 8.687L2.03711 8.687M8.69562 15.3132L8.69563 21.972M8.69562 15.3132L15.3218 15.3133M8.69562 15.3132L2.03793 15.313M15.3221 2.02853L15.3219 8.687M15.3219 8.687L15.3218 15.3133M15.3219 8.687L21.9495 8.687M15.3218 15.3133L15.3217 21.9714M15.3218 15.3133L21.9808 15.3135");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.xvjk-cbox {
  d: path("M12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22Z");
}

</style>
