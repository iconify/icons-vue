<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="y3zoshb4k"/><path class="qxxrgx6kr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ambulance-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qxxrgx6kr {
  d: path("M9 10h1a1 1 0 0 1 0 2H9v1a1 1 0 0 1-2 0v-1H6a1 1 0 0 1 0-2h1V9a1 1 0 0 1 2 0Zm-4.764 6.832a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m10 0a3 3 0 1 1 5.527 2.338a3 3 0 0 1-5.527-2.338m-7.943 1.875a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414m10 0a.999.999 0 1 0 1.414-1.414a.999.999 0 1 0-1.414 1.414");
}

.y3zoshb4k {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v2h3c.265 0 .52.105.707.293l4 4A1 1 0 0 1 22 12v6a1 1 0 0 1-1 1h-1.171a3 3 0 0 1-5.658 0H9.829a3 3 0 0 1-5.658 0H3a1 1 0 0 1-1-1Zm12 7h5.586l-3-3H14Zm-7.709 6.705l.002.002l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 0 1.41m11.414.004l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 1.414 1.414");
}

</style>
