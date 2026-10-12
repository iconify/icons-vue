<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyd950bko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:geyser-sharp" /></template>
<style>
.vyd950bko {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.07 20.74l1.11-1.73l.32-.51h15l.32.51l1.11 1.73l.32.51H2.75zM12 15.5V4.25m0 0L9.312 2.714L7.5 5.25m4.5-1l2.688-1.536L16.5 5.25M6.5 15l-1.125-1.125L6.5 12.75l1.125-1.125L6.5 10.5m11 4.5l-1.125-1.125L17.5 12.75l1.125-1.125L17.5 10.5");
}

</style>
