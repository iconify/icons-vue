<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="fye12pb5g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:flow-arrow-bold" /></template>
<style>
.fye12pb5g {
  fill: currentColor;
  d: path("m248.49 71.51l-32-32a12 12 0 0 0-17 17L211 68h-3c-52 0-64.8 30.71-75.08 55.38c-8.82 21.17-15.45 37.05-42.75 40.09a44 44 0 1 0 .28 24.08c43.34-3.87 55.07-32 64.63-54.93C164.9 109 172 92 208 92h3l-11.52 11.51a12 12 0 0 0 17 17l32-32a12 12 0 0 0 .01-17M48 196a20 20 0 1 1 20-20a20 20 0 0 1-20 20");
}

</style>
