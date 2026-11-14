<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aux5fwxid"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gender-pay-gap" /></template>
<style>
.aux5fwxid {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.875 16.75h4.25A1.375 1.375 0 0 1 9.5 18.125A1.375 1.375 0 0 1 8.125 19.5h-4.25A1.375 1.375 0 0 1 2.5 18.125a1.375 1.375 0 0 1 1.375-1.375m.5-2.75h4.25A1.375 1.375 0 0 1 10 15.375a1.375 1.375 0 0 1-1.375 1.375h-4.25A1.375 1.375 0 0 1 3 15.375A1.375 1.375 0 0 1 4.375 14m-.5-2.75h4.25A1.375 1.375 0 0 1 9.5 12.625A1.375 1.375 0 0 1 8.125 14h-4.25A1.375 1.375 0 0 1 2.5 12.625a1.375 1.375 0 0 1 1.375-1.375m.5-2.75h4.25A1.375 1.375 0 0 1 10 9.875a1.375 1.375 0 0 1-1.375 1.375h-4.25A1.375 1.375 0 0 1 3 9.875A1.375 1.375 0 0 1 4.375 8.5m-.5-2.75h4.25A1.375 1.375 0 0 1 9.5 7.125A1.375 1.375 0 0 1 8.125 8.5h-4.25A1.375 1.375 0 0 1 2.5 7.125A1.375 1.375 0 0 1 3.875 5.75m11.5 11h4.25A1.375 1.375 0 0 1 21 18.125a1.375 1.375 0 0 1-1.375 1.375h-4.25A1.375 1.375 0 0 1 14 18.125a1.375 1.375 0 0 1 1.375-1.375m.5-2.75h4.25a1.375 1.375 0 0 1 1.375 1.375a1.375 1.375 0 0 1-1.375 1.375h-4.25a1.375 1.375 0 0 1-1.375-1.375A1.375 1.375 0 0 1 15.875 14M16 5.75h3.5m-1.75 0v5.5m-1.75 0h3.5");
}

</style>
