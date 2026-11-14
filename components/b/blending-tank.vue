<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="re19-d-ej"/><path class="b2t92fb4g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blending-tank" /></template>
<style>
.b2t92fb4g {
  d: path("M4.5 10.5q3.75-2 7.5 0t7.5 0M12 2.25V14.5m-3 0h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.re19-d-ej {
  d: path("M4.5 18.5v-9a7.5 5 0 0 1 15 0v9Zm2 0v3m11-3v3");
}

</style>
