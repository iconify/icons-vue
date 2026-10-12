<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="aqly3mz2l"/><path class="n9l5kfbfl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:accessible-entrance" /></template>
<style>
.aqly3mz2l {
  d: path("M8.75 21.25V4.75a2 2 0 0 1 2-2h8.5a2 2 0 0 1 2 2v16.5m-12.5 0h12.5m-18 0h5q.5 0 .5-.5v-3.5q0-.5-.4-.2l-5.2 3.9q-.4.3.1.3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n9l5kfbfl {
  d: path("M12 12h5m-2-2l2 2l-2 2");
}

</style>
