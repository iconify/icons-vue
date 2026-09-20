<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wu-svqt-l"/><path class="hlkk9_bki"/><path class="tb3ak12-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:game-avatar-outline-thin" /></template>
<style>
.hlkk9_bki {
  d: path("M7 10c0 4 2 6 5 6s5 -2 5 -6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tb3ak12-o {
  d: path("M6 21v-3h12v3");
}

.wu-svqt-l {
  d: path("M7 10V5h10v5");
}

</style>
