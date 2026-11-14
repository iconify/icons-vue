<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bdy5jq4he"/><path class="ydfbtcy3i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:kids-scooter-three-wheel" /></template>
<style>
.bdy5jq4he {
  d: path("m4.5 19.5l2-4h8.75m-2.5 4L16 14l3.5 5.5M16 14L14.5 3.5m-2.5 0h5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ydfbtcy3i {
  d: path("M2.5 19.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m8.25 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m6.75 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0");
}

</style>
