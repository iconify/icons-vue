<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="st3u6g13n"/><path class="v3e-9pb4m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:bell-simple-z-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.st3u6g13n {
  d: path("M208 192H48a8 8 0 0 1-6.88-12C47.71 168.6 56 139.81 56 104a72 72 0 0 1 144 0c0 35.82 8.3 64.6 14.9 76a8 8 0 0 1-6.9 12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v3e-9pb4m {
  d: path("M168 224a8 8 0 0 1-8 8H96a8 8 0 1 1 0-16h64a8 8 0 0 1 8 8m-24-88h-17l23.7-35.56A8 8 0 0 0 144 88h-32a8 8 0 0 0 0 16h17.05l-23.7 35.56A8 8 0 0 0 112 152h32a8 8 0 0 0 0-16m77.84 56a15.8 15.8 0 0 1-13.84 8H48a16 16 0 0 1-13.8-24.06C39.75 166.38 48 139.34 48 104a80 80 0 1 1 160 0c0 35.33 8.26 62.38 13.81 71.94a15.89 15.89 0 0 1 .03 16.06M208 184c-7.73-13.27-16-43.95-16-80a64 64 0 1 0-128 0c0 36.06-8.28 66.74-16 80Z");
}

</style>
