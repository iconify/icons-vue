<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bydbpacnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:champagne-pop-sharp" /></template>
<style>
.bydbpacnr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.15 8.75h2.6v2.5l.57.7l1.11 1.35l.57.7v7.25H8V14l.57-.7l1.11-1.35l.57-.7v-2.5zM8 16.5h8M10.75 3h2.5v3h-2.5zm-2.5 1.75l-1.75-1m9.25 1l1.75-1m-9 3.5l-1.75.5m8.75-.5l1.75.5");
}

</style>
