<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="wi98cxe4x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:greater-than-or-equal-bold" /></template>
<style>
.wi98cxe4x {
  fill: currentColor;
  d: path("M51.85 148.74L173.29 104L51.85 59.26a12 12 0 0 1 8.3-22.52l152 56a12 12 0 0 1 0 22.52l-152 56a12 12 0 1 1-8.3-22.52M208 188H56a12 12 0 0 0 0 24h152a12 12 0 0 0 0-24");
}

</style>
