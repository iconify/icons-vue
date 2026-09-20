<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dt7zp_wra"/><path class="x50q_4bdr"/><path class="s3pa5qb5b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:iceberg-table-outline-regular" /></template>
<style>
.dt7zp_wra {
  d: path("M12 4.5 14.5 7h-5Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s3pa5qb5b {
  d: path("M7 13h10l-5 5Z");
}

.x50q_4bdr {
  d: path("M3 10h18");
}

</style>
