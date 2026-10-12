<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zumom1f2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:compost-pile" /></template>
<style>
.zumom1f2o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.28 20.4L9.97 9.6q.53-.85 1.06 0l6.69 10.8q.53.85-.47.85H3.75q-1 0-.47-.85m4.47-4.9h5.5M5.5 18.75h10m-1.25-6.25L19 4.75m-1-1l2.25 1.5");
}

</style>
