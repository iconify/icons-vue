<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yr4oprbwi"/><path class="o56x81bpl"/><path class="s_vl9ialg"/><path class="kk7jzcbcv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:digital-loyalty-card" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kk7jzcbcv {
  d: path("M10 19h4");
}

.o56x81bpl {
  d: path("M8.75 7.5h6.5A1.75 1.75 0 0 1 17 9.25v5A1.75 1.75 0 0 1 15.25 16h-6.5A1.75 1.75 0 0 1 7 14.25v-5A1.75 1.75 0 0 1 8.75 7.5");
}

.s_vl9ialg {
  fill: currentColor;
  d: path("m12.367 9.869l.016.036a1.5 1.5 0 0 0 1.253.911l.039.003a.399.399 0 0 1 .227.699l-.03.026a1.5 1.5 0 0 0-.478 1.473l.009.039a.399.399 0 0 1-.595.431l-.033-.02a1.5 1.5 0 0 0-1.55 0l-.033.02a.399.399 0 0 1-.595-.431l.009-.039a1.5 1.5 0 0 0-.478-1.473l-.03-.026a.399.399 0 0 1 .227-.699l.039-.003a1.5 1.5 0 0 0 1.253-.911l.016-.036a.399.399 0 0 1 .734 0");
}

.yr4oprbwi {
  d: path("M8.5 2.5h7A3.5 3.5 0 0 1 19 6v12a3.5 3.5 0 0 1-3.5 3.5h-7A3.5 3.5 0 0 1 5 18V6a3.5 3.5 0 0 1 3.5-3.5m2 2.5h3");
}

</style>
