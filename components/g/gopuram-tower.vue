<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nd_7h-blp"/><path class="esd8pabbd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:gopuram-tower" /></template>
<style>
.esd8pabbd {
  d: path("M10.5 21.25v-2.5a1.5 1.5 0 0 1 3 0v2.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nd_7h-blp {
  d: path("M4.25 20.85V17.9q0-.4.4-.4h.45q.4 0 .4-.4v-2.7q0-.4.4-.4h.45q.4 0 .4-.4v-2.7q0-.4.4-.4h.45q.4 0 .4-.4V7.4q0-.4.4-.4h7.2q.4 0 .4.4v2.7q0 .4.4.4h.45q.4 0 .4.4v2.7q0 .4.4.4h.45q.4 0 .4.4v2.7q0 .4.4.4h.45q.4 0 .4.4v2.95q0 .4-.4.4H4.65q-.4 0-.4-.4M8 7V5.75A1.75 1.75 0 0 1 9.75 4h4.5A1.75 1.75 0 0 1 16 5.75V7Zm2-3V2.75M14 4V2.75");
}

</style>
