<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zzj3efbkg"/><path class="lmmpfhbuy"/><path class="fg8blactd"/><path class="q8z93hbyf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:carry-out-service" /></template>
<style>
.fg8blactd {
  fill: currentColor;
  d: path("M14.5 16.75h7l-.5 5h-6Z");
}

.lmmpfhbuy {
  d: path("M5 16a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm6-10v4.5");
}

.q8z93hbyf {
  d: path("m16.25 16.75l.75-2.5h2l.75 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zzj3efbkg {
  d: path("M11.541 15.5H2.5v-4l2.5-1L7.5 6H15l3 4.5l2.462.985");
}

</style>
