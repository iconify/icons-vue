<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p84nvubdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:diwali-diya-sharp" /></template>
<style>
.p84nvubdb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5c1.25 1.75 2.5 3.1 2.5 4.5a2.5 2.5 0 0 1-5 0c0-1.4 1.25-2.75 2.5-4.5ZM3 13.75h18a9 6.75 0 0 1-18 0Z");
}

</style>
