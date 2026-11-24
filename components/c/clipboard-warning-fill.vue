<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p2xrxurdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clipboard-warning-fill" /></template>
<style>
.p2xrxurdq {
  fill: currentColor;
  d: path("M16 4h1a3 3 0 0 1 3 3v12a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h1a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2M8 6H7a.997.997 0 0 0-1 1v12a1 1 0 0 0 1 1h10a1 1 0 0 0 1-1V7a1 1 0 0 0-1-1h-1a2 2 0 0 1-2 2h-4a2 2 0 0 1-2-2m5 5v3a1 1 0 0 1-2 0v-3a1 1 0 0 1 2 0m-1 5h.01a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2");
}

</style>
