<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t_h61xbju"/><path class="b4nc3bcfk"/><path class="voktf9o_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eye-patch" /></template>
<style>
.b4nc3bcfk {
  fill: currentColor;
  d: path("M5.75 10.75a3 2.5 0 1 0 6 0a3 2.5 0 1 0-6 0Z");
}

.t_h61xbju {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0ZM3 8l18-1.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.voktf9o_r {
  d: path("M15.5 10.75h.01M9.5 16.5h5");
}

</style>
