<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="u1dy4x0_k"/><path class="wjclvfbbb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:gem-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.u1dy4x0_k {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m17.243 14.669l-3.162 3.513a2.8 2.8 0 0 1-4.162 0l-6.393-7.103a3 3 0 0 1 .109-4.128l1.486-1.487A5 5 0 0 1 8.657 4h6.686c1.326 0 2.598.527 3.536 1.464l1.486 1.487a3 3 0 0 1 .109 4.128Z");
}

.wjclvfbbb {
  d: path("M10.707 10.293a.999.999 0 1 1-1.414 1.414l-2-2a.999.999 0 1 1 1.414-1.414Z");
}

</style>
