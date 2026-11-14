<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="cb_a5zmpo"/><path class="b87v0ov7y"/><path class="g5b17yx9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:deal-competitor" /></template>
<style>
.b87v0ov7y {
  fill: currentColor;
  d: path("M2.5 21c0-3.5 2.5-5.75 6-5.75s6 2.25 6 5.75Z");
}

.cb_a5zmpo {
  d: path("M13.5 5.25a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0m.5 5.5c2.501-.455 5.208.331 6.43 1.981M5.5 9.25a3 3 0 1 0 6 0a3 3 0 1 0-6 0");
}

.g5b17yx9m {
  d: path("m20.5 15.5l-3 3.25h2.75L17.5 21.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
