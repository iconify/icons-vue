<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="wss69fbzz"/><path class="xsazwm5ho"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:blanket-chest" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wss69fbzz {
  d: path("M3 11V8.5a4 4 0 0 1 4-4h10a4 4 0 0 1 4 4V11Zm1.75 0h14.5A1.75 1.75 0 0 1 21 12.75v6a1.75 1.75 0 0 1-1.75 1.75H4.75A1.75 1.75 0 0 1 3 18.75v-6A1.75 1.75 0 0 1 4.75 11M7.5 4.5v16m9-16v16");
}

.xsazwm5ho {
  d: path("M12 9za1.5 1.5 0 0 1 1.5 1.5V12a1.5 1.5 0 0 1-1.5 1.5a1.5 1.5 0 0 1-1.5-1.5v-1.5A1.5 1.5 0 0 1 12 9");
}

</style>
