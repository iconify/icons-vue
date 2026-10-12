<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdhrv1bdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:cutlery-sharp" /></template>
<style>
.cdhrv1bdq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 2.75v4a2.5 2.5 0 0 0 5 0v-4m-2.5 0v18.5m8.5-1.75v-5.25h-.75V7.5c0-2.6 1.35-4.75 3.25-4.75h.25V19.5l-.117 1.37h-2.75z");
}

</style>
