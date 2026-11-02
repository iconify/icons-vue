<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="v-wwl8b5v"/><path class="z92kh9bgt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:alarm-off-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.v-wwl8b5v {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20.67 15.427L9.573 4.33a9 9 0 0 1 8.787 2.302a9.02 9.02 0 0 1 2.31 8.795M6.714 5.714l12.572 12.572A9.001 9.001 0 1 1 6.714 5.714");
}

.z92kh9bgt {
  d: path("m3.707 1.293l19 19a.999.999 0 1 1-1.414 1.414L5 5.414L3.707 6.707a.999.999 0 1 1-1.414-1.414L3.586 4L2.293 2.707a.999.999 0 1 1 1.414-1.414m15 1l3 3a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 1.414-1.414");
}

</style>
