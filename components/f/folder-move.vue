<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xafs9n1fe"/><path class="r-1iinbid"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:folder-move" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r-1iinbid {
  d: path("M8.5 15h7M13 12.75L15.5 15L13 17.25");
}

.xafs9n1fe {
  d: path("M2.75 7.25a2.5 2.5 0 0 1 2.5-2.5h3.6a2 2 0 0 1 1.6.8L11.55 7a2 2 0 0 0 1.6.8h5.6a2.5 2.5 0 0 1 2.5 2.5v6.45a2.5 2.5 0 0 1-2.5 2.5H5.25a2.5 2.5 0 0 1-2.5-2.5Zm0 3.5h18.5");
}

</style>
