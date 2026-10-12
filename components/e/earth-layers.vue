<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="irkzavb_i"/><path class="vn_r12b4c"/><path class="cdm38lf2a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:earth-layers" /></template>
<style>
.cdm38lf2a {
  d: path("M12 6a6 6 0 0 1 6 6m-6 0V9a3 3 0 0 1 3 3Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.irkzavb_i {
  d: path("M12 12V2.75A9.25 9.25 0 1 0 21.25 12Z");
}

.vn_r12b4c {
  d: path("M6.5 8.75c1-.4 2 0 2.25 1s-.25 1.5.5 2.25s1.5 1.25 1 2.25s-1.75 1-2.5.25s-.6-1.6-1.4-2.2s-.85-1.3-.7-2.15c.1-.65.35-1.15.85-1.4m5.5-6A9.25 9.25 0 0 1 21.25 12");
}

</style>
