<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xvjk-cbox"/><path class="wrski3b_o"/><path class="qzritzb0s"/><path class="kga3h3bmu"/><path class="xypkzkhmd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:branching-paths-down-linear" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kga3h3bmu {
  stroke-linejoin: round;
  d: path("M8 16.5H6M7.5 18L6 16.5L7.5 15");
}

.qzritzb0s {
  d: path("M16 16.5C13.7909 16.5 12 14.7091 12 12.5V6.5");
}

.wrski3b_o {
  stroke-linejoin: round;
  d: path("M16 16.5H18M16.5 18L18 16.5L16.5 15");
}

.xvjk-cbox {
  d: path("M12 22C7.28595 22 4.92893 22 3.46447 20.5355C2 19.0711 2 16.714 2 12C2 7.28595 2 4.92893 3.46447 3.46447C4.92893 2 7.28595 2 12 2C16.714 2 19.0711 2 20.5355 3.46447C22 4.92893 22 7.28595 22 12C22 16.714 22 19.0711 20.5355 20.5355C19.0711 22 16.714 22 12 22Z");
}

.xypkzkhmd {
  d: path("M8 16.5C10.2091 16.5 12 14.7091 12 12.5V6.5");
}

</style>
