<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="a10sg6bpd"/><path class="a703x8s7m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chess-duotone-sharp" /></template>
<style>
.a10sg6bpd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m8 17l2-6H7L6 9l4-3l-1-3l3 1c3.041 1.017 3.999 4.075 4 7v6h2v4H6v-4Z");
}

.a703x8s7m {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m8 17l2-6H7L6 9l4-3l-1-3l3 1c3 1 4 4 4 7v6M6 17h12v4H6Z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
