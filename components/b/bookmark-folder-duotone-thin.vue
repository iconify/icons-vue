<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r0jamibkm"/><path class="lql2z9jat"/><path class="bn_pu6j-z"/><path class="ss9ca_5lc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:bookmark-folder-duotone-thin" /></template>
<style>
.bn_pu6j-z {
  d: path("M20 7v13H4V4h5l3 3h4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lql2z9jat {
  fill: currentColor;
  d: path("M10 10h4v7l-2 -2 -2 2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.r0jamibkm {
  fill: currentColor;
  d: path("M20 7v13H4V4h5l3 3h4");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ss9ca_5lc {
  d: path("M10 10h4v7l-2 -2 -2 2Z");
}

</style>
