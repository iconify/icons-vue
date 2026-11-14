<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkoaooaqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:code-of-conduct-dev" /></template>
<style>
.bkoaooaqv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.3 19H3V2.5h13v9.3M6.5 7h6m-3.25 4h3.25m-6 4H10m8.25 6.25l-3-3a2.125 2.125 0 0 1 3-3a2.125 2.125 0 0 1 3 3Z");
}

</style>
