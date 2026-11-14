<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xxzildb7p"/><path class="m90ufg8yb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:bank-kiosk" /></template>
<style>
.m90ufg8yb {
  d: path("M9.618 7.125a2.75 2.75 0 0 1 4.764 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xxzildb7p {
  d: path("M3.5 3h17l-1.75 9H5.25Zm6.5 9v7m4-7v7m-8 0h12v2.5H6Zm6-10.5h.01");
}

</style>
