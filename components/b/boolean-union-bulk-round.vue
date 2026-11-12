<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq_7myjag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:boolean-union-bulk-round" /></template>
<style>
.wq_7myjag {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M5 2h8a3 3 0 0 1 3 3v2a.997.997 0 0 0 1 1h2a3 3 0 0 1 3 3v8a3 3 0 0 1-3 3h-8a3 3 0 0 1-3-3v-2a.997.997 0 0 0-1-1H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3");
}

</style>
