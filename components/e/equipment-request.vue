<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x0z0qhd6q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:equipment-request" /></template>
<style>
.x0z0qhd6q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.2 15H4.5V3h15v9.2M15.2 21H2.5v-3.5h9.7m9.3 3.3v.2h-.7M18 15v6m-3-3h6");
}

</style>
