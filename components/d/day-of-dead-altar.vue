<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d7qlftblc"/><path class="yx_rcr38i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:day-of-dead-altar" /></template>
<style>
.d7qlftblc {
  d: path("M2.5 21.5v-3h3v-3H8v-3h8v3h2.5v3h3v3Zm7-9V7m0-2.75h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yx_rcr38i {
  d: path("M12.5 9.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0m3 0h.01");
}

</style>
