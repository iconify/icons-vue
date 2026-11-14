<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ocyf5ip6z"/><path class="g-gifkbwy"/><path class="t2vua2bow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cognitive-access" /></template>
<style>
.g-gifkbwy {
  d: path("M11.75 7C10 5.75 7.5 6.75 8 9c-1 1.5 0 4.5 2.25 4.25c.5 1 2.5 1 3 0C15.5 13.5 16.5 10.5 15.5 9c.5-2.25-2-3.25-3.75-2");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ocyf5ip6z {
  d: path("M8 21.5v-4c-2.5-1.75-3.5-4.25-3.5-7C4.5 6.25 7.75 3 12 3c4 0 7 2.75 7 6.75l1.5 3.5c.25.5-.1 1-.75 1H19v2.25c0 1.1-.9 2-2 2h-2v3");
}

.t2vua2bow {
  d: path("M11.75 7c-.75 2 .75 3.75 0 6.75");
}

</style>
