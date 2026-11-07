<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="btj469bbu"/><path class="g518znrlf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-taped-bulk" /></template>
<style>
.btj469bbu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 7.063v9.871a2 2 0 0 1-1.114 1.793l-8 3.951l-.004.002a2 2 0 0 1-.864.205h-.036a2 2 0 0 1-.868-.207l-8-3.951A2 2 0 0 1 2 16.934V7.066a2 2 0 0 1 1.114-1.793l3.257-1.608L16.5 8.667l2.258-1.116L8.629 2.549l2.485-1.227a2 2 0 0 1 .872-.207h.028c.303.003.6.073.872.207l8.002 3.952A2 2 0 0 1 22 7.063");
}

.cuyn6tgcc {
  fill: currentColor;
}

.g518znrlf {
  d: path("m12 9.774l8.397-4.147a1 1 0 1 1 .886 1.793L13 11.51v10.375a1 1 0 0 1-2 0V11.51L2.717 7.42a1 1 0 0 1 .886-1.793Z");
}

</style>
