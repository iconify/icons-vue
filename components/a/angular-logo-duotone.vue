<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="iw2gxwbiu"/><path class="fde7k68my"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:angular-logo-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.fde7k68my {
  d: path("m227.08 64.62l-96-40a7.93 7.93 0 0 0-6.16 0l-96 40a8 8 0 0 0-4.85 8.44l16 120a8 8 0 0 0 4.35 6.1l80 40a8 8 0 0 0 7.16 0l80-40a8 8 0 0 0 4.35-6.1l16-120a8 8 0 0 0-4.85-8.44m-26.45 122.12L128 223.06l-72.63-36.32L40.74 77L128 40.67L215.26 77ZM121 84.12l-40 72a8 8 0 1 0 14 7.76L106 144h44l11 19.88a8 8 0 1 0 14-7.76l-40-72a8 8 0 0 0-14 0M141.07 128h-26.14L128 104.47Z");
}

.iw2gxwbiu {
  d: path("m224 72l-16 120l-80 40l-80-40L32 72l96-40Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
