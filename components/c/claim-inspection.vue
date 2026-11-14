<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_9mrccvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:claim-inspection" /></template>
<style>
.a_9mrccvk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m2.5 10.5l5-5l5 5V18h-10Zm10.5 4a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Zm6 2.5l2 2");
}

</style>
