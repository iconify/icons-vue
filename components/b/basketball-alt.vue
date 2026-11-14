<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="irft8w7vr"/><path class="h_z5eeykk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:basketball-alt" /></template>
<style>
.h_z5eeykk {
  d: path("M12 2.5c-.25 5-4.5 9.25-9.5 9.5m9.5 9.5c.25-5 4.5-9.25 9.5-9.5");
}

.irft8w7vr {
  d: path("M2.5 12a9.5 9.5 0 1 0 19 0a9.5 9.5 0 1 0-19 0Zm16.218-6.718L5.282 18.718m0-13.436l13.436 13.436");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
