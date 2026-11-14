<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="li-51-1gk"/><path class="zwrd0eb_n"/><path class="u3fq0ebgr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:compact-tractor" /></template>
<style>
.li-51-1gk {
  d: path("M12 16.5h7.5A1.5 1.5 0 0 0 21 15v-2.5a1.5 1.5 0 0 0-1.5-1.5h-7V4.5a1 1 0 0 0-1-1H5a1 1 0 0 0-1 1V10");
}

.u3fq0ebgr {
  d: path("M6 16.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zwrd0eb_n {
  d: path("M3 16.5a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0Zm13.25 2.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0Z");
}

</style>
