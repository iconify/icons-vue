<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxf3dbcsa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:face-wink-fill-round" /></template>
<style>
.pxf3dbcsa {
  fill: currentColor;
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12m7.01-4H9a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M16 8h-2a1 1 0 0 0 0 2h2a1 1 0 0 0 0-2m-7.293 5.293a.999.999 0 1 0-1.414 1.414a6.653 6.653 0 0 0 9.414 0a1.002 1.002 0 0 0-1.414-1.414a4.656 4.656 0 0 1-6.586 0");
}

</style>
