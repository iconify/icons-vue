<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="imb_sqbzq"/><path class="k-guyyfgd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:iron-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.imb_sqbzq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m2.293 17.293l7-7A1 1 0 0 1 10 10h11a1 1 0 0 1 1 1v7a1 1 0 0 1-1 1H3a1.002 1.002 0 0 1-.707-1.707");
}

.k-guyyfgd {
  d: path("M14 11V6a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v5a1 1 0 0 1-2 0V7h-4v4a1 1 0 0 1-2 0");
}

</style>
