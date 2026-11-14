<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vspug48qm"/><path class="hkugkfbiy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:holiday-calendar-star" /></template>
<style>
.hkugkfbiy {
  d: path("m12 11.75l.75 2.5h2.75l-2 1.75l.75 2.5L12 17l-2.25 1.5l.75-2.5l-2-1.75h2.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vspug48qm {
  d: path("M3 4.5h18V21H3Zm5-2v3.75m8-3.75v3.75M3 9h18");
}

</style>
