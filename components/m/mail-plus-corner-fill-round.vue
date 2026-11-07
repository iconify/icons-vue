<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v3pbl7bpg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mail-plus-corner-fill-round" /></template>
<style>
.v3pbl7bpg {
  fill: currentColor;
  d: path("M7.536 9.121L3.677 5.263A4.98 4.98 0 0 1 7 4h10c1.228 0 2.406.445 3.323 1.263l-3.859 3.858a3 3 0 0 1-2.121.879H9.657a3 3 0 0 1-2.121-.879M21 12h-4.586l5.117-5.117c.31.664.47 1.384.469 2.117v2a1 1 0 0 1-1 1M3.234 7.648l2.887 2.888A5 5 0 0 0 9.657 12H12v7a1 1 0 0 1-1 1H7a5 5 0 0 1-5-5V9c0-.733.158-1.453.469-2.117ZM19 15v2h2a1 1 0 0 1 0 2h-2v2a1 1 0 0 1-2 0v-2h-2a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0");
}

</style>
