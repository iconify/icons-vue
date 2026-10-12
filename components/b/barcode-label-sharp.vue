<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b4a1b6bah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:barcode-label-sharp" /></template>
<style>
.b4a1b6bah {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 4.75h16.5v14.5H2.75V4.75zm1.5 3v6.5m2.25-6.5v6.5m2.5-6.5v6.5m2.25-6.5v6.5m2.25-6.5v6.5m2.25-6.5v6.5m-9.25 2.5h7");
}

</style>
