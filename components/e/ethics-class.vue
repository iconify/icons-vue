<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhhohue2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ethics-class" /></template>
<style>
.dhhohue2t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5v17m-6 0h12M4.5 6.5h15M2.5 12h6c0 3.5-6 3.5-6 0Zm3-5.5V12m10 0h6c0 3.5-6 3.5-6 0Zm3-5.5V12");
}

</style>
