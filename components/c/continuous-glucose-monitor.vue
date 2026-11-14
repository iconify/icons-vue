<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ef6z0dbai"/><path class="hetiejouj"/><path class="o22_7nb8b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:continuous-glucose-monitor" /></template>
<style>
.ef6z0dbai {
  d: path("M3 14a7 7 0 1 0 14 0a7 7 0 1 0-14 0Z");
}

.hetiejouj {
  fill: currentColor;
  d: path("M10 9.5c1.75 2.25 3 3.75 3 5.25a3 3 0 0 1-6 0c0-1.5 1.25-3 3-5.25Z");
}

.o22_7nb8b {
  d: path("M16 5.25A2.75 2.75 0 0 1 18.75 8M16 2.75A5.25 5.25 0 0 1 21.25 8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
