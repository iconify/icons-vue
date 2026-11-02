<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="dtk8q2bdi"/><path class="nkgl2ob8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:car-electric-side-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dtk8q2bdi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 12c0-.265.105-.52.293-.707l5-5A1 1 0 0 1 8 6h5c.265 0 .52.105.707.293L18.414 11H21a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1h-1.171a3 3 0 0 1-5.658 0H9.829a3 3 0 0 1-5.658 0H3a1 1 0 0 1-1-1Zm4.291 6.705l.002.002l.002.002a1 1 0 0 0 1.41 0l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 0 1.41m11.414.004l.002-.002l.002-.002a1 1 0 0 0 0-1.41l-.002-.002l-.002-.002a1 1 0 0 0-1.41 0l-.002.002l-.002.002a1 1 0 0 0 1.414 1.414");
}

.nkgl2ob8y {
  d: path("m11.707 10.707l-.293.293H13a1.002 1.002 0 0 1 .707 1.707l-2 2a.999.999 0 1 1-1.414-1.414l.293-.293H9a1.002 1.002 0 0 1-.707-1.707l2-2a.999.999 0 1 1 1.414 1.414M4 18a3 3 0 1 1 6 0a3 3 0 0 1-6 0m10 0a3 3 0 1 1 6 0a3 3 0 0 1-6 0m-8 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0m10 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
