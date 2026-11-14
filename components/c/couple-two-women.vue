<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aeov1kzfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:couple-two-women" /></template>
<style>
.aeov1kzfi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 13V8.5a3 3 0 0 1 6 0V13M5 8.5a3 3 0 0 0 6 0M2.5 21c0-3 2.25-5 5.5-5c1.629 0 2.881.502 3.724 1.381m1.259 3.118Q13 20.745 13 21m.75-11V6a2.75 2.75 0 0 1 5.5 0v4m-5.5-4a2.75 2.75 0 0 0 5.5 0M18 21.5c-2-1.5-3.5-2.75-3.5-4.5c0-1.25 1-2.25 2-2.25c.75 0 1.25.5 1.5 1c.25-.5.75-1 1.5-1c1 0 2 1 2 2.25c0 1.75-1.5 3-3.5 4.5Z");
}

</style>
