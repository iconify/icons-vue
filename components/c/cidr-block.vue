<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cthgp42vw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:cidr-block" /></template>
<style>
.cthgp42vw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 2.5H8V8H2.5Zm8.5 0h5.5V8H11ZM2.5 11H8v5.5H2.5Zm8.5 0h5.5v5.5H11Zm6 10.5l4.5-8");
}

</style>
