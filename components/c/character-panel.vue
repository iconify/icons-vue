<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s_i6cia1i"/><path class="cn9iodbjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:character-panel" /></template>
<style>
.cn9iodbjp {
  d: path("m6.823 15.943l.784-1.961a1.5 1.5 0 0 1 2.786 0l.784 1.961A1.5 1.5 0 0 1 9.784 18H8.216a1.5 1.5 0 0 1-1.393-2.057M7 15.5h4m4-3.5h3m-3 4h2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s_i6cia1i {
  d: path("M6.5 3h11A3.5 3.5 0 0 1 21 6.5v11a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17.5v-11A3.5 3.5 0 0 1 6.5 3M3 7.5h18");
}

</style>
