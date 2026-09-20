<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="ijgfo6b_g"/><path class="ym0o9qbap"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:bread-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ijgfo6b_g {
  d: path("M208 111v89a8 8 0 0 1-8 8h-56a8 8 0 0 0 8-8v-89a32 32 0 0 0-8-63h56a32 32 0 0 1 8 63");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ym0o9qbap {
  d: path("M240 80a40 40 0 0 0-40-40H48a40 40 0 0 0-16 76.65V200a16 16 0 0 0 16 16h152a16 16 0 0 0 16-16v-83.35A40.06 40.06 0 0 0 240 80M48 120a8 8 0 0 0 0-16a24 24 0 0 1 0-48h96a24 24 0 0 1 0 48a8 8 0 0 0 0 16v80H48Zm152-16a8 8 0 0 0 0 16v80h-40v-83.35A40 40 0 0 0 176 56h24a24 24 0 0 1 0 48");
}

</style>
