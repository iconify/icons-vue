<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt9-nqjsw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:door-closing-warning" /></template>
<style>
.zt9-nqjsw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 9.75h6.5V21.5H4Zm9.5 0H20V21.5h-6.5ZM9.5 7a3.5 3.5 0 0 1 5 0M8 4.5a6.5 6.5 0 0 1 8 0");
}

</style>
