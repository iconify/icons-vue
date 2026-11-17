<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="v8xhjm3ii"/><path class="pdmz-r1yt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-wifi-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.pdmz-r1yt {
  d: path("M14.581 13.002A7.4 7.4 0 0 1 17 12.597a7.38 7.38 0 0 1 4.625 1.622a1 1 0 0 1-1.25 1.562a5.4 5.4 0 0 0-1.609-.888A5.4 5.4 0 0 0 17 14.597a5.4 5.4 0 0 0-1.766.296a5.4 5.4 0 0 0-1.609.888a1 1 0 0 1-1.25-1.562a7.4 7.4 0 0 1 2.206-1.217m.979 3.45a3.8 3.8 0 0 1 1.44-.28a3.82 3.82 0 0 1 2.707 1.121a.999.999 0 1 1-1.414 1.414A1.82 1.82 0 0 0 17 18.172a1.82 1.82 0 0 0-1.293.535a1.002 1.002 0 0 1-1.414-1.414a3.8 3.8 0 0 1 1.267-.841M17.01 20a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2Z");
}

.v8xhjm3ii {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.714 9H12a3 3 0 0 0-3 3v9a1 1 0 0 1-1 1a5 5 0 0 1-3.536-1.464A4.98 4.98 0 0 1 3 17v-5.185a5 5 0 0 1 1.707-3.763l4-3.5a5 5 0 0 1 6.586 0l3.08 2.695A1.001 1.001 0 0 1 17.714 9");
}

</style>
