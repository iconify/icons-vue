<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="v8xhjm3ii"/><path class="gnyryjbyz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-pin-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.gnyryjbyz {
  d: path("M20 12a1 1 0 0 1 0 2v1.586l.707.707c.311.31.456.752.382 1.186C20.928 18.428 19.898 19 19 19h-1v2a1 1 0 0 1-2 0v-2h-1c-.898 0-1.928-.572-2.089-1.521a1.34 1.34 0 0 1 .382-1.186l.707-.707V14a1 1 0 0 1 0-2Z");
}

.v8xhjm3ii {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.714 9H12a3 3 0 0 0-3 3v9a1 1 0 0 1-1 1a5 5 0 0 1-3.536-1.464A4.98 4.98 0 0 1 3 17v-5.185a5 5 0 0 1 1.707-3.763l4-3.5a5 5 0 0 1 6.586 0l3.08 2.695A1.001 1.001 0 0 1 17.714 9");
}

</style>
