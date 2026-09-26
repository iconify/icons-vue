<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="s1z-h0jxx"/><path class="askejtgvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-image-sharp" /></template>
<style>
.askejtgvc {
  fill: currentColor;
  d: path("M10.5 7C10.5 7.8284 9.8284 8.5 9 8.5C8.1716 8.5 7.5 7.8284 7.5 7C7.5 6.1716 8.1716 5.5 9 5.5C9.8284 5.5 10.5 6.1716 10.5 7Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s1z-h0jxx {
  d: path("M14 2L4 2L4 22L20 22L20 8L14 2ZM14 2L14 8L20 8M4 18L9.9999 12.0001L20 17");
}

</style>
