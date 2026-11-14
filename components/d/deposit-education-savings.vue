<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cva0gw_7i"/><path class="p71haabjo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deposit-education-savings" /></template>
<style>
.cva0gw_7i {
  d: path("M4 13.5c0-3.5 3.6-6 8-6s8 2.5 8 6c0 2.2-1.3 4-3.5 5V21H14v-1.75c-.65.15-1.3.25-2 .25s-1.35-.1-2-.25V21H7.5v-2.5c-2.2-1-3.5-2.8-3.5-5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.p71haabjo {
  d: path("M4.5 12h-2v3h2M9.75 3.75l1.522-.845a1.5 1.5 0 0 1 1.456 0l1.522.845a1.43 1.43 0 0 1 0 2.5l-1.522.845a1.5 1.5 0 0 1-1.456 0L9.75 6.25a1.43 1.43 0 0 1 0-2.5M16.5 5l.75 2.5m-9.5 4.75h.01");
}

</style>
