<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="dx3ubrb9h"/><path class="hbtmd5b0k"/><path class="dy9tza2iq"/><path class="k7qu5ueqh"/><path class="c9ga8t7-s"/><path class="f-5fmfwpk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:judge-rubric-outline-bold" /></template>
<style>
.c9ga8t7-s {
  d: path("M11 11.5a2 2 0 0 1 -4 0");
}

.dx3ubrb9h {
  d: path("M4 7.5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2V19a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.dy9tza2iq {
  d: path("M8 10.5h8");
}

.f-5fmfwpk {
  d: path("M17 11.5a2 2 0 0 1 -4 0");
}

.hbtmd5b0k {
  d: path("M9.5 7V2.5h5V7");
}

.k7qu5ueqh {
  d: path("M12 12v4.5");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
