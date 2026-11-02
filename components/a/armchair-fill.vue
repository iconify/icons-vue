<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ciqmf2bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:armchair-fill" /></template>
<style>
.ciqmf2bac {
  fill: currentColor;
  d: path("M5 8.171V6a3 3 0 0 1 3-3h8a3 3 0 0 1 3 3v2.171A3 3 0 0 1 21 11v5c0 1.27-.803 2.405-2 2.829V20a1 1 0 0 1-2 0v-1H7v1a1 1 0 0 1-2 0v-1.171A3 3 0 0 1 3 16v-5c0-1.27.803-2.405 2-2.829M17 6a1 1 0 0 0-1-1H8a.997.997 0 0 0-1 1v2.171A3 3 0 0 1 9 11a.997.997 0 0 0 1 1h4a.997.997 0 0 0 1-1a3 3 0 0 1 2-2.829Z");
}

</style>
