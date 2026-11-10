<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bnaok_blw"/><path class="woqoq5bwt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-horizontal-space-around-sharp-duotone" /></template>
<style>
.bnaok_blw {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M15 6C15.552 6 16 6.448 16 7V17C16 17.552 15.552 18 15 18H9C8.448 18 8 17.552 8 17V7C8 6.448 8.448 6 9 6H15Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.woqoq5bwt {
  d: path("M5 1V23H3V1H5ZM21 1V23H19V1H21Z");
}

</style>
