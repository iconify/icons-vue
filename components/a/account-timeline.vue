<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gn-qlxbnr"/><path class="z7k7ekb_d"/><path class="zcdte3bzk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-timeline" /></template>
<style>
.gn-qlxbnr {
  d: path("M12 3.75A8.25 8.25 0 1 1 3.75 12");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z7k7ekb_d {
  d: path("M2 13.75L3.75 12l1.75 1.75M8 12a4 4 0 1 0 8 0a4 4 0 1 0-8 0Z");
}

.zcdte3bzk {
  d: path("M12 9.5V12l1.75 1");
}

</style>
