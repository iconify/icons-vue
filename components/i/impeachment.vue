<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrklg37_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:impeachment" /></template>
<style>
.wrklg37_g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.376 7.735l3.359-3.359a2.625 2.625 0 0 1 3.712 0l.177.177a2.625 2.625 0 0 1 0 3.712l-3.359 3.359a2.625 2.625 0 0 1-3.712 0l-.177-.177a2.625 2.625 0 0 1 0-3.712M11 10l5.5 5.5m-3.5 3h7a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-7a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
