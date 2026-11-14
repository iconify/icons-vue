<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="eh4k9abqy"/><path class="pn9tifbbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ai-explain" /></template>
<style>
.eh4k9abqy {
  d: path("M12.215 18.843A8 8 0 0 0 12 19c-3-2.25-6.5-2.5-9.5-1.5v-13c3-1 6.5-.75 9.5 1.5c3-2.25 6.5-2.5 9.5-1.5v10.77M12 6v13");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pn9tifbbp {
  d: path("M18.25 15q.5 2.75 3.25 3.25q-2.75.5-3.25 3.25q-.5-2.75-3.25-3.25q2.75-.5 3.25-3.25");
}

</style>
