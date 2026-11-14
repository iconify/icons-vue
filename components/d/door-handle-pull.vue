<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s_-mj0rqn"/><path class="wm948pixd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:door-handle-pull" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s_-mj0rqn {
  d: path("M6 21.5v-17a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v17m-14.5 0h17");
}

.wm948pixd {
  d: path("M13 7.5h1.75v9H13");
}

</style>
