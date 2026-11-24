<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="braf_dipk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-shield-corner-fill" /></template>
<style>
.braf_dipk {
  fill: currentColor;
  d: path("M19 10h-8a.997.997 0 0 0-1 1v10a1 1 0 0 1-1 1H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6c.265 0 .52.105.707.293l6 6A1 1 0 0 1 19 10m-2-2l-4-4v2a2 2 0 0 0 2 2Zm-3 4h6a2 2 0 0 1 2 2v2c-.001 3.075-1.94 4.852-4.629 5.928a1 1 0 0 1-.742 0C13.94 20.852 12.001 19.075 12 16v-2a2 2 0 0 1 2-2");
}

</style>
