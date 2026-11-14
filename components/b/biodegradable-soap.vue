<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hq7n66bao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:biodegradable-soap" /></template>
<style>
.hq7n66bao {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.272 8.75q.39-6.5 7.728-6.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 4.524-5.441 6.572q.628.38 1.184.935q1.757 1.758 1.757 4.243v.5q0 2.485-1.757 4.243q-1.758 1.757-4.243 1.757h-5.5q-2.485 0-4.243-1.757Q1.75 17.735 1.75 15.25v-.5q0-2.485 1.757-4.243Q5.265 8.75 7.75 8.75zm-.147 2.75h-5.25Q4.5 11.5 4.5 14.875v.25q0 3.375 3.375 3.375h5.25q3.375 0 3.375-3.375v-.25q0-3.375-3.375-3.375");
}

</style>
