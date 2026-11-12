<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bh85_p_7j"/><path class="h0wraxb-n"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-taped-bulk" /></template>
<style>
.bh85_p_7j {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 7.066v9.868a2 2 0 0 1-1.114 1.793l-8 3.951a2 2 0 0 1-1.772 0l-8-3.951A2 2 0 0 1 2 16.934V7.066a2 2 0 0 1 1.114-1.793l8-3.951a2 2 0 0 1 1.772 0l8 3.951A2 2 0 0 1 22 7.066");
}

.cuyn6tgcc {
  fill: currentColor;
}

.h0wraxb-n {
  d: path("m17.629 6.994l2.768-1.367a1 1 0 1 1 .886 1.793L18.08 9.002l-.016.007L13 11.51v10.375a1 1 0 0 1-2 0V11.51L2.717 7.42a1 1 0 0 1 .886-1.793L12 9.774l3.371-1.665l-7.185-3.548a.999.999 0 1 1 .886-1.793Z");
}

</style>
