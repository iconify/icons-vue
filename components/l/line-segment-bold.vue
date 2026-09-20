<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qsnhsgl1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:line-segment-bold" /></template>
<style>
.qsnhsgl1d {
  fill: currentColor;
  d: path("M217.47 38.53a36 36 0 0 0-57.95 41l-80 80a36.07 36.07 0 0 0-41 7a36 36 0 1 0 58 9.95l80-80a36 36 0 0 0 41-57.95Zm-145 162a12 12 0 1 1 0-17a12 12 0 0 1 .01 16.97Zm128-128a12 12 0 0 1-17 0a12 12 0 1 1 17 0");
}

</style>
