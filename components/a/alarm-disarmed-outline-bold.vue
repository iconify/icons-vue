<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="c2nlsybqj"/><path class="zshu2cj5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:alarm-disarmed-outline-bold" /></template>
<style>
.c2nlsybqj {
  d: path("M12 3s4 2 8 3v6c0 5 -4 8 -8 9 -4 -1 -8 -4 -8 -9V6c4 -1 8 -3 8 -3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zshu2cj5h {
  d: path("m8 15 8 -8");
}

</style>
