<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f05dbwbtr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-chevron-double-up-fill-round" /></template>
<style>
.f05dbwbtr {
  fill: currentColor;
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12m12.293-1.293a.999.999 0 1 0 1.414-1.414l-3-3a.997.997 0 0 0-1.414 0l-3 3a.999.999 0 1 0 1.414 1.414L12 8.414Zm0 6a.999.999 0 1 0 1.414-1.414l-3-3a1 1 0 0 0-1.414 0l-3 3a.999.999 0 1 0 1.414 1.414L12 14.414Z");
}

</style>
