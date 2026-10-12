<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ad0wssbps"/><path class="s2pihbcct"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ketchup-bottle-sharp" /></template>
<style>
.ad0wssbps {
  d: path("M10.1 9h4.4l-.22-.56l-2.06-5.13l-.22-.56l-.22.56l-2.06 5.13L9.5 9zM7 9h10v12.25H7z");
}

.s2pihbcct {
  d: path("M12 13.75c-1.2-.5-2.5.3-2.5 1.85a2.5 2.5 0 0 0 5 0c0-1.55-1.3-2.35-2.5-1.85Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
