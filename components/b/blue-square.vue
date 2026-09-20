<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="izn5yrbfq"/><path class="jsbw_bc3o"/><path class="hi-8ox32e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:blue-square" /></template>
<style>
.hi-8ox32e {
  fill: var(--svg-color--fff, #fff);
  d: path("M39.7 12.9c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4c-1.9 2.3-2.3 5.6-2.6 8.4c-.2 2.2-2.2 14.9 3.5 11.2c.68-.45 1.23-1.07 1.6-1.8c1.2-2.1 1.9-3.5 3.3-5.6c5.3-8.6 18.8-10.5 18.8-13.5");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.izn5yrbfq {
  fill: var(--svg-color--0d47a1, #0d47a1);
  d: path("M116 4H12c-4.42 0-8 3.58-8 8v104c0 4.42 3.58 8 8 8h104c4.42 0 8-3.58 8-8V12c0-4.42-3.58-8-8-8");
}

.jsbw_bc3o {
  fill: var(--svg-color--1976d2, #1976d2);
  d: path("M109.7 4H11.5A7.555 7.555 0 0 0 4 11.5v97.9c-.01 4.14 3.34 7.49 7.48 7.5h98.12c4.14.01 7.49-3.34 7.5-7.48V11.5c.09-4.05-3.13-7.41-7.18-7.5z");
}

</style>
