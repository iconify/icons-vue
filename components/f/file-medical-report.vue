<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jam7pt4mt"/><path class="hxab50gmd"/><path class="b_21y31ym"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:file-medical-report" /></template>
<style>
.b_21y31ym {
  fill: currentColor;
  d: path("M19.75 18.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.hxab50gmd {
  d: path("M14.75 14.25V16c0 1.5 1 2.5 2.25 2.5s2.25-1 2.25-2.5v-1.75M17 18.5v1c0 1.25.75 2 2 2c1 0 1.75-.75 1.75-1.75");
}

.jam7pt4mt {
  d: path("M12.8 19H3V2.5h13v8.9M6 7h7m-7 3.5h7M6 14h4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
