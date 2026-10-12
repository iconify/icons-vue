<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qhu-0fb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:launch-tower-sharp" /></template>
<style>
.qhu-0fb4g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.5 21.25V2.75H8v18.5m-4.5-15l4.5 3l-4.5 3l4.5 3l-4.5 3M8 7.5h4.25m4-4.75l3 2.368V19h-6V5.118zm-13.5 18.5h18.5");
}

</style>
