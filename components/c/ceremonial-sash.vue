<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="t1d0ypb-c"/><path class="u4vc26bod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ceremonial-sash" /></template>
<style>
.t1d0ypb-c {
  d: path("M3 20.75v-12c0-2.5 1.5-4 4-4.5l2.5-1q2.5 2.5 5 0l2.5 1c2.5.5 4 2 4 4.5v12M7 4.25L14.75 12M3.5 6.5L12 15");
}

.u4vc26bod {
  d: path("M12 14.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm1 2.25l-1.25 3.5m4.25-3.5l1.25 3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
