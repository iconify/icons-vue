<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bw3_j9bkm"/><path clip-rule="evenodd" class="tng8jzb7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-left-to-line-sharp-two-tone" /></template>
<style>
.bw3_j9bkm {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13.877 5.418L8.198 10.999H23V12.999H8.198L13.877 18.58L12.476 20.006L5.054 12.712C4.862 12.524 4.754 12.267 4.754 11.999C4.754 11.731 4.862 11.474 5.054 11.286L12.476 3.992L13.877 5.418Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.tng8jzb7c {
  fill-rule: evenodd;
  d: path("M3 4V20H1V4H3Z");
}

</style>
