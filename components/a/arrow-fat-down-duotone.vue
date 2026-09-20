<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="fp1838bci"/><path class="f2hmsgnvc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:arrow-fat-down-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f2hmsgnvc {
  d: path("M231.39 132.94A8 8 0 0 0 224 128h-40V48a16 16 0 0 0-16-16H88a16 16 0 0 0-16 16v80H32a8 8 0 0 0-5.66 13.66l96 96a8 8 0 0 0 11.32 0l96-96a8 8 0 0 0 1.73-8.72M128 220.69L51.31 144H80a8 8 0 0 0 8-8V48h80v88a8 8 0 0 0 8 8h28.69Z");
}

.fp1838bci {
  d: path("m224 136l-96 96l-96-96h48V48a8 8 0 0 1 8-8h80a8 8 0 0 1 8 8v88Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
