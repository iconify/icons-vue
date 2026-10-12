<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ac5hihblu"/><path class="lbxv7ysiu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:confetti-burst-sharp" /></template>
<style>
.ac5hihblu {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.54 8.01l-2.25-.83l-.47-.17l.17-.47l.83-2.25l.17-.47l.47.17l2.25.83l.47.17l-.17.47l-.83 2.25l-.17.47zm13.27 9.52l-2.18 1.02l-.45.21l-.21-.45l-1.02-2.18l-.21-.45l.45-.21l2.18-1.02l.45-.21l.21.45l1.02 2.18l.21.45zM7 19.21L5.73 17.7l-.32-.38l.38-.32l1.51-1.27l.38-.32l.32.38l1.27 1.51l.32.38l-.38.32l-1.51 1.27l-.38.32zm6-13.46c1-1.25 2-.25 3-1.25s2 .25 3-1M3.5 12.25c1.25-1 2.25.25 3.25-.75s2 .25 3.25-.5m3.25 1.5c1 1.25 2.25.5 3 1.75");
}

.lbxv7ysiu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M19.5 9h.01M13 20h.01M11.25 8.5h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
