<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jad6bkbgv"/><path class="fkyz1kbww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fkyz1kbww {
  d: path("m12 9.774l8.237-4.069a1.002 1.002 0 0 1 .886 1.794L13 11.51v10.259a1 1 0 0 1-2 0V11.51L2.877 7.499a1.002 1.002 0 0 1 .886-1.794Z");
}

.jad6bkbgv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 7.687v8.626a3 3 0 0 1-1.672 2.69l-7 3.456a3 3 0 0 1-2.656 0l-7-3.456A3 3 0 0 1 2 16.313V7.687c0-1.141.648-2.184 1.672-2.69l7-3.456a3 3 0 0 1 2.656 0l7 3.456A3 3 0 0 1 22 7.687");
}

</style>
