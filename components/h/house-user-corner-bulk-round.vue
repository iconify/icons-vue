<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="v8xhjm3ii"/><path class="dewy5e9yf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-user-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dewy5e9yf {
  d: path("M14.236 12.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m2.057 1.875a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414m-2.902 4.979c1.425-2.245 5.793-2.245 7.218 0c.25.394.391.846.391 1.314a1 1 0 0 1-2 0a.46.46 0 0 0-.08-.243c-.21-.331-.661-.535-1.024-.637A3.3 3.3 0 0 0 17 20a3.3 3.3 0 0 0-.896.12c-.363.102-.814.306-1.024.637A.46.46 0 0 0 15 21a1 1 0 0 1-2 0c0-.468.141-.92.391-1.314");
}

.v8xhjm3ii {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.714 9H12a3 3 0 0 0-3 3v9a1 1 0 0 1-1 1a5 5 0 0 1-3.536-1.464A4.98 4.98 0 0 1 3 17v-5.185a5 5 0 0 1 1.707-3.763l4-3.5a5 5 0 0 1 6.586 0l3.08 2.695A1.001 1.001 0 0 1 17.714 9");
}

</style>
