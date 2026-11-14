<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s_096vbct"/><path class="tion8w9ud"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bald-eagle-flying" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s_096vbct {
  d: path("M12 8.5c-2 0-5-1.5-9.5-2l2.5 5l4.5 1L10 14l-1.5 5h7L14 14l.5-1.5l4.5-1l2.5-5c-4.5.5-7.5 2-9.5 2");
}

.tion8w9ud {
  d: path("M10.25 6.75a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
