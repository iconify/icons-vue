<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ay7u2rbhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:flame-alt-fill" /></template>
<style>
.ay7u2rbhm {
  fill: currentColor;
  d: path("m14.115 21.788l-.001.001A1 1 0 0 1 13.5 22h-3a1 1 0 0 1-.614-.211h-.001q-.626-.483-1.179-1.046c-2.558-2.464-4.132-5.449-3.295-9.069c.366-1.579 1.132-3.045 2.017-4.391c.883-1.339 1.899-2.584 2.912-3.825q.443-.54.879-1.083a1 1 0 0 1 1.562 0q.436.544.879 1.083c.5.613 1 1.226 1.485 1.851c1.464 1.887 2.899 4.014 3.444 6.365c.837 3.62-.737 6.605-3.295 9.069q-.553.563-1.179 1.045M10.851 20h2.298c.655-.54 1.308-1.185 1.67-1.966a2.58 2.58 0 0 0 .153-1.774c-.208-.77-.69-1.469-1.19-2.079c-.542-.66-1.154-1.261-1.782-1.838c-.628.577-1.24 1.178-1.782 1.838c-.5.61-.982 1.309-1.19 2.079a2.58 2.58 0 0 0 .153 1.774c.362.781 1.015 1.426 1.67 1.966");
}

</style>
