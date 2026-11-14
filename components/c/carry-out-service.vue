<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="w189nac1q"/><path class="vuhn_dh3p"/><path class="sajda5xjk"/><path class="q8z93hbyf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:carry-out-service" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q8z93hbyf {
  d: path("m16.25 16.75l.75-2.5h2l.75 2.5");
}

.sajda5xjk {
  fill: currentColor;
  d: path("M16.157 16.75h3.686a1.5 1.5 0 0 1 1.492 1.649l-.2 2a1.5 1.5 0 0 1-1.492 1.351h-3.286a1.5 1.5 0 0 1-1.492-1.351l-.2-2a1.5 1.5 0 0 1 1.492-1.649");
}

.vuhn_dh3p {
  d: path("M5 16a2 2 0 1 0 4 0a2 2 0 1 0-4 0m6-10v4.5");
}

.w189nac1q {
  d: path("M12.841 15.5H2.5v-4l2.5-1L7.5 6H15l3 4.5l2.5 1v.359");
}

</style>
