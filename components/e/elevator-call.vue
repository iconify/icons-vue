<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="bp72sbbsp"/><path class="rq866kbao"/><path class="ln-k0e6ba"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:elevator-call" /></template>
<style>
.bp72sbbsp {
  d: path("M4.5 2.5h15a1 1 0 0 1 1 1v17a1 1 0 0 1-1 1h-15a1 1 0 0 1-1-1v-17a1 1 0 0 1 1-1Z");
}

.ln-k0e6ba {
  d: path("M9.5 12L12 9.5l2.5 2.5M12 9.5V15");
}

.rq866kbao {
  d: path("M6.5 12a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
