<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ygdyhpteb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hand-grab-bulk-sharp" /></template>
<style>
.ygdyhpteb {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3 15v-2.5a1.5 1.5 0 0 1 1.256-1.48h.002l.004-.001A1.5 1.5 0 0 1 6 12.5V15a.5.5 0 0 0 1 0V9a1.999 1.999 0 0 1 3.001-1.732C10.619 7.626 11 8.285 11 9v3a.5.5 0 0 0 1 0V9a1.999 1.999 0 0 1 3-1.732c.619.357 1 1.017 1 1.732v3a.5.5 0 0 0 1 0V9a1.999 1.999 0 0 1 3-1.732c.619.357 1 1.017 1 1.732v6a7 7 0 0 1-7 7h-4a7 7 0 0 1-7-7");
}

</style>
