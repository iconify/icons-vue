<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p11nwgb3z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-help-corner-fill" /></template>
<style>
.p11nwgb3z {
  fill: currentColor;
  d: path("m13.707 2.293l6 6A1 1 0 0 1 19 10h-8a.997.997 0 0 0-1 1v10a1 1 0 0 1-1 1H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6c.265 0 .52.105.707.293M13 4v2a2 2 0 0 0 2 2h2Zm1 12a3 3 0 1 1 3 3a1 1 0 0 1 0-2a1.001 1.001 0 0 0 .707-1.707a1 1 0 0 0-1.094-.215A.99.99 0 0 0 16 16a1 1 0 0 1-2 0m3 4h.01a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2");
}

</style>
