<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="iwnnrs6eq"/><path class="uf7nv3nlu"/><path class="tdveuibbn"/><path class="e88rd2ult"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:hard-drive-backup" /></template>
<style>
.e88rd2ult {
  d: path("m8.75 7.5l1.75-1v2.25");
}

.iwnnrs6eq {
  d: path("M3 12h18v8H3Z");
}

.tdveuibbn {
  d: path("M13.607 6.585a2.5 2.5 0 1 1-3.214 0");
}

.uf7nv3nlu {
  d: path("m3.5 12.5l2.5-7a1.5 1.5 0 0 1 1.5-1h9a1.5 1.5 0 0 1 1.5 1l2.5 7M7 16h.01M10 16h.01");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
