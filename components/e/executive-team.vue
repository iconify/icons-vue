<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbj0pczmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:executive-team" /></template>
<style>
.bbj0pczmt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 2.5za1.32 1.32 0 0 1 1.269 1.683l-.434 1.519a1.5 1.5 0 0 0-.045.606l1.381 10.586a1.5 1.5 0 0 1-.287 1.095L5.875 19a1.406 1.406 0 0 1-2.25 0l-.759-1.011a1.5 1.5 0 0 1-.287-1.095L3.96 6.308a1.5 1.5 0 0 0-.045-.606l-.434-1.519A1.32 1.32 0 0 1 4.75 2.5m7.25 0za1.32 1.32 0 0 1 1.269 1.683l-.434 1.519a1.5 1.5 0 0 0-.045.606l1.381 10.586a1.5 1.5 0 0 1-.287 1.095L13.125 19a1.406 1.406 0 0 1-2.25 0l-.759-1.011a1.5 1.5 0 0 1-.287-1.095L11.21 6.308a1.5 1.5 0 0 0-.045-.606l-.434-1.519A1.32 1.32 0 0 1 12 2.5m7.25 0za1.32 1.32 0 0 1 1.269 1.683l-.434 1.519a1.5 1.5 0 0 0-.045.606l1.381 10.586a1.5 1.5 0 0 1-.287 1.095L20.375 19a1.406 1.406 0 0 1-2.25 0l-.759-1.011a1.5 1.5 0 0 1-.287-1.095L18.46 6.308a1.5 1.5 0 0 0-.045-.606l-.434-1.519A1.32 1.32 0 0 1 19.25 2.5M4 6h1.5m5.75 0h1.5m5.75 0H20");
}

</style>
