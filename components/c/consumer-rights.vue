<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku4llziwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:consumer-rights" /></template>
<style>
.ku4llziwm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4H5l2.5 11.5h5.831m2.9 0h1.1m.225-.224L19.5 7.5H6m1 12a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Zm5.514.205q.016.119.052.234t.088.223q.053.108.123.207t.154.184t.182.157t.204.126q.108.055.222.092q.115.037.234.055M14.75 18l2 2L21 15.75");
}

</style>
