<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="b-5hy_w3c"/><path class="eip9xqkzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:houses-duotone" /></template>
<style>
.b-5hy_w3c {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M3 21v-6.717c0-.577.249-1.126.683-1.506l3-2.625a2 2 0 0 1 2.634 0l3 2.625c.434.38.683.929.683 1.506V21Z");
}

.eip9xqkzw {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13 21h8m-8 0H3v-6.717a2 2 0 0 1 .683-1.506l3-2.625a2 2 0 0 1 2.634 0l3 2.625A2 2 0 0 1 13 14.283zm0-14h.01M17 7h.01M17 11h.01M17 15h.01M9 9.875V3h10a2 2 0 0 1 2 2v16");
}

.ft5dv1b6b {
  fill: none;
}

</style>
