<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xza1z9bee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-code-fill-sharp" /></template>
<style>
.xza1z9bee {
  fill: currentColor;
  d: path("M13 2c.265 0 .52.105.707.293l6 6A1 1 0 0 1 20 9v12a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm0 7h5l-5-5Zm-5.707 6.707l2 2a.999.999 0 1 0 1.414-1.414L9.414 15l1.293-1.293a.999.999 0 1 0-1.414-1.414l-2 2a.997.997 0 0 0 0 1.414m7.414-3.414a.999.999 0 1 0-1.414 1.414L14.586 15l-1.293 1.293a.999.999 0 1 0 1.414 1.414l2-2a1 1 0 0 0 0-1.414Z");
}

</style>
