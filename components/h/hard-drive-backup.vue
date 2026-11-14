<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g4f94qb1r"/><path class="uf7nv3nlu"/><path class="tdveuibbn"/><path class="e88rd2ult"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hard-drive-backup" /></template>
<style>
.e88rd2ult {
  d: path("m8.75 7.5l1.75-1v2.25");
}

.g4f94qb1r {
  d: path("M6.5 12h11a3.5 3.5 0 0 1 3.5 3.5v1a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 16.5v-1A3.5 3.5 0 0 1 6.5 12");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tdveuibbn {
  d: path("M13.607 6.585a2.5 2.5 0 1 1-3.214 0");
}

.uf7nv3nlu {
  d: path("m3.5 12.5l2.5-7a1.5 1.5 0 0 1 1.5-1h9a1.5 1.5 0 0 1 1.5 1l2.5 7M7 16h.01M10 16h.01");
}

</style>
