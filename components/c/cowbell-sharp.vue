<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsw5xcc2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cowbell-sharp" /></template>
<style>
.lsw5xcc2q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 7h6l.26.97l2.98 11.06l.26.97H3l.26-.97L6.24 7.97L6.5 7zm1 0V3.75h3V7M3.81 17h12.38m5.06-14L17 7.25");
}

</style>
