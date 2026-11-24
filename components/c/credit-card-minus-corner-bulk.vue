<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zv0ky1bfi"/><path class="rgwj2d5qw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:credit-card-minus-corner-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.rgwj2d5qw {
  d: path("M3 8h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2m18 7a1 1 0 0 1 0 2h-8a1 1 0 0 1 0-2Z");
}

.zv0ky1bfi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 7v2H10v10a1 1 0 0 1-1 1H5a3 3 0 0 1-3-3V7a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3");
}

</style>
