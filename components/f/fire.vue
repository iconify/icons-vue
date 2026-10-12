<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qh_gzwezd"/><path class="uh74l-bpr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fire" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qh_gzwezd {
  d: path("M12 21.25a6.75 6.75 0 0 0 6.75-6.75c0-4.25-3-6.5-4.5-11.75c-1 2.75-2.25 4-3.75 5.25c-.5-1-1-1.75-1.75-2.5c-2.25 2.5-3.5 5-3.5 9A6.75 6.75 0 0 0 12 21.25");
}

.uh74l-bpr {
  d: path("M12 18.75a2.5 2.5 0 0 0 2.5-2.5c0-1.5-1-2.5-2.5-4.25c-1.5 1.75-2.5 2.75-2.5 4.25a2.5 2.5 0 0 0 2.5 2.5");
}

</style>
