<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mbo8ih4aw"/><path class="awarh9xws"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:crossbuck-sign" /></template>
<style>
.awarh9xws {
  d: path("m5.815 10.75l10.649-7.457a1.5 1.5 0 0 1 2.089.368a1.5 1.5 0 0 1-.368 2.089L7.536 13.207a1.5 1.5 0 0 1-2.089-.368a1.5 1.5 0 0 1 .368-2.089M12 8.25V21.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mbo8ih4aw {
  d: path("m7.536 3.293l10.649 7.457a1.5 1.5 0 0 1 .368 2.089a1.5 1.5 0 0 1-2.089.368L5.815 5.75a1.5 1.5 0 0 1-.368-2.089a1.5 1.5 0 0 1 2.089-.368");
}

</style>
