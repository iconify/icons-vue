<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mevpu5b8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:final-assembly" /></template>
<style>
.mevpu5b8q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.3 13.5H4.5V3h15v10.3m-17 .2h16.8M4.5 6.75h15M12 3v3.75M14.75 18l2 2L21 15.75");
}

</style>
