<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="u__n76blo"/><path class="ivc0p9bus"/><path class="gnhsdzb8d"/><path class="t-ezw9csu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:file-storage-outline-bold" /></template>
<style>
.gnhsdzb8d {
  d: path("M6 13h6");
}

.ivc0p9bus {
  d: path("M6 4h12");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.t-ezw9csu {
  d: path("M6 16h9");
}

.u__n76blo {
  d: path("M2 10a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

</style>
