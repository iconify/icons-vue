<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="csoib1fkd"/><rect class="bu59-29xe"/><path class="f5mq_kvnb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:honeypot" /></template>
<style>
.bu59-29xe {
  width: 14.5px;
  height: 3.5px;
  x: 4.75px;
  y: 4px;
  rx: 1.5px;
}

.csoib1fkd {
  d: path("M6 7.5h12l.5 1.5c1.5 4.5 1.5 8.25-1 11.5a2 2 0 0 1-1.6.75H8.1a2 2 0 0 1-1.6-.75C4 17.25 4 13.5 5.5 9Z");
}

.f5mq_kvnb {
  d: path("M8.75 7.5v3a1.25 1.25 0 0 0 2.5 0v-1a1 1 0 0 1 2 0v2a1.25 1.25 0 0 0 2.5 0v-4Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
