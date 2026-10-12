<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mfnjzkrjs"/><rect class="kmgwxaclg"/><path class="ae0h5kb0o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:erlenmeyer" /></template>
<style>
.ae0h5kb0o {
  d: path("M9 15h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kmgwxaclg {
  width: 4px;
  height: 2.5px;
  x: 10px;
  y: 2.75px;
  rx: 1px;
}

.mfnjzkrjs {
  d: path("M10.75 7.5h2.5v3.91a5 5 0 1 1-2.5 0Z");
}

</style>
