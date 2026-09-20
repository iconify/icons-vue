<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b7uyqxwtl"/><path class="rcr3_oykt"/><path class="l1--aac0s"/><path class="ky4omnbla"/><path class="vrzboac1q"/><path class="ipav-zhpr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:balance-sheet-duotone-thin" /></template>
<style>
.b7uyqxwtl {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ipav-zhpr {
  d: path("M14.5 8.5v7");
}

.ky4omnbla {
  d: path("M4 5h14l4 4v8a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2V7a2 2 0 0 1 2 -2m14 0v4h4");
}

.l1--aac0s {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M14.5 8.5v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rcr3_oykt {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M9.5 8.5v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.vrzboac1q {
  d: path("M9.5 8.5v7");
}

</style>
