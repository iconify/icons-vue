<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="pc0c2jb-q"/><path class="e3p_qubua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:cloud-fog-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e3p_qubua {
  d: path("M120 208H72a8 8 0 0 1 0-16h48a8 8 0 0 1 0 16m64-16h-24a8 8 0 0 0 0 16h24a8 8 0 0 0 0-16m-24 32h-56a8 8 0 0 0 0 16h56a8 8 0 0 0 0-16m72-124a76.08 76.08 0 0 1-76 76H76a52 52 0 0 1 0-104a53 53 0 0 1 8.92.76A76.08 76.08 0 0 1 232 100m-16 0a60.06 60.06 0 0 0-120-3.54a8 8 0 0 1-16-.92q.21-3.66.77-7.23A38 38 0 0 0 76 88a36 36 0 0 0 0 72h80a60.07 60.07 0 0 0 60-60");
}

.pc0c2jb-q {
  d: path("M224 100a68 68 0 0 1-68 68H76a44 44 0 1 1 14.2-85.66v.11A68.06 68.06 0 0 1 224 100");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
