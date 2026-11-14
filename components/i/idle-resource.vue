<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tnp-usbdl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:idle-resource" /></template>
<style>
.tnp-usbdl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.7 13H2.5V3.5h17v9.2m-13-4.45h.01m3.49 0h5.5m6 10.25a3 3 0 1 1-3-3a3 3 0 0 0 3 3Z");
}

</style>
