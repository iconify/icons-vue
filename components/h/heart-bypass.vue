<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dg3bgkbnj"/><path class="ghs4l6boo"/><path class="k4197bbdr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:heart-bypass" /></template>
<style>
.dg3bgkbnj {
  d: path("M14.025 8.678c-1.056.292-2.04.572-3.025.572L8 9c-3.5.5-5 4-4.5 7C4 18.5 5 20.5 6 21c.935.467 3.181-.376 5.512-1.305");
}

.ghs4l6boo {
  d: path("M11 9.25v-2.5c0-2 1.5-3 3.25-3c.71 0 1.379.165 1.923.494M12.5 4.5l-.5-2m2.25 1.25V2M16 4l.5-1.75m1 5.25C21.75 10 21.25 17 14.25 19");
}

.k4197bbdr {
  d: path("M17 10.5c1.5 2 .75 5-3.25 6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
