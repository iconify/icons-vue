<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hmxgz1ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:boolean-intersect-fill-round" /></template>
<style>
.hmxgz1ble {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h2a1 1 0 0 1 0 2H5a.997.997 0 0 0-1 1v2a1 1 0 0 1-2 0Zm11-3a3 3 0 0 1 3 3a1 1 0 0 1-2 0a.997.997 0 0 0-1-1h-2a1 1 0 0 1 0-2Zm-2 6h2a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3v-2a3 3 0 0 1 3-3m11 3v2a1 1 0 0 1-2 0v-2a1 1 0 0 0-1-1a1 1 0 0 1 0-2a3 3 0 0 1 3 3M4 13a.997.997 0 0 0 1 1a1 1 0 0 1 0 2a3 3 0 0 1-3-3v-2a1 1 0 0 1 2 0Zm18 6a3 3 0 0 1-3 3h-2a1 1 0 0 1 0-2h2a1 1 0 0 0 1-1v-2a1 1 0 0 1 2 0Zm-11 1h2a1 1 0 0 1 0 2h-2a3 3 0 0 1-3-3a1 1 0 0 1 2 0a1 1 0 0 0 1 1");
}

</style>
