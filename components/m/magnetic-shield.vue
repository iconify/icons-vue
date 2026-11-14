<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5m2z7brf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:magnetic-shield" /></template>
<style>
.q5m2z7brf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 3l5 1.75V11c0 4.5-2 8-5 10c-3-2-5-5.5-5-10V4.75ZM2.5 7q3.5 5 0 10m19-10q-3.5 5 0 10");
}

</style>
