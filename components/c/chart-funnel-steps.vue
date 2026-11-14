<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n3ik-4bkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:chart-funnel-steps" /></template>
<style>
.n3ik-4bkt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 3h19v5h-3v5.5h-3V18h-2v3.5h-3V18h-2v-4.5h-3V8h-3Zm3 5h13m-10 5.5h7");
}

</style>
