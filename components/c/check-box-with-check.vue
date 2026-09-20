<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kvpk03zso"/><path class="sus6njbpf"/><path clip-rule="evenodd" class="xmpk6rbzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:check-box-with-check" /></template>
<style>
.kvpk03zso {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.86 7.85h112.28v112.29H7.86z");
}

.sus6njbpf {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M124.54.47H3.47C1.82.47.48 1.81.48 3.46v121.07c0 1.64 1.34 2.99 2.99 2.99h121.07c1.64 0 2.99-1.35 2.99-2.99V3.46c-.01-1.64-1.36-2.99-2.99-2.99m-4.4 119.67H7.86V7.85h112.28z");
}

.xmpk6rbzm {
  fill: var(--svg-color--ed6c30, #ed6c30);
  fill-rule: evenodd;
  d: path("m116.12 34.88l-9.32-9.33l-57.68 58.24L21.2 56.04l-9.32 9.33l37.28 37.07l5.92-5.92l-.02-.03z");
}

</style>
