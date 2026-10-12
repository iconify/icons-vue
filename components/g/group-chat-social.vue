<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="qs4t2u6su"/><path class="t1ov0-q9j"/><circle class="l-zqvscmh"/><circle class="um74zsb4n"/><path class="qv6ad4bzu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:group-chat-social" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l-zqvscmh {
  cx: 7.5px;
  cy: 11px;
  r: 1.25px;
}

.qs4t2u6su {
  d: path("M7.25 4.75a2 2 0 0 1 2-2h10a2 2 0 0 1 2 2V11a2 2 0 0 1-2 2v2.5l-2-2");
}

.qv6ad4bzu {
  d: path("M5.5 15a2 2 0 0 1 4 0m.5 0a2 2 0 0 1 4 0");
}

.t1ov0-q9j {
  d: path("M2.75 9.5A2.5 2.5 0 0 1 5.25 7h9a2.5 2.5 0 0 1 2.5 2.5v6a2.5 2.5 0 0 1-2.5 2.5h-5L6.5 20.5a.77.77 0 0 1-1.25-.6V18a2.5 2.5 0 0 1-2.5-2.5Z");
}

.um74zsb4n {
  cx: 12px;
  cy: 11px;
  r: 1.25px;
}

</style>
