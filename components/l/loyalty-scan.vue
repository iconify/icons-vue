<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lxn5kub-l"/><path class="bkod4yx2d"/><path class="faidsgbop"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:loyalty-scan" /></template>
<style>
.bkod4yx2d {
  fill: currentColor;
  d: path("m10.588 9.191l.236.58a1.5 1.5 0 0 0 1.279.929l.625.046a.635.635 0 0 1 .363 1.118l-.478.404a1.5 1.5 0 0 0-.489 1.504l.15.607a.635.635 0 0 1-.951.691l-.532-.33a1.5 1.5 0 0 0-1.582 0l-.532.33a.635.635 0 0 1-.951-.691l.15-.607a1.5 1.5 0 0 0-.489-1.504l-.478-.404a.635.635 0 0 1 .363-1.118l.625-.046a1.5 1.5 0 0 0 1.279-.929l.236-.58a.635.635 0 0 1 1.176 0");
}

.faidsgbop {
  d: path("M16 10v4");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lxn5kub-l {
  d: path("M2.5 7V4.5a2 2 0 0 1 2-2H7m10 0h2.5a2 2 0 0 1 2 2V7m0 10v2.5a2 2 0 0 1-2 2H17m-10 0H4.5a2 2 0 0 1-2-2V17M7.625 6h8.75A2.625 2.625 0 0 1 19 8.625v6.75A2.625 2.625 0 0 1 16.375 18h-8.75A2.625 2.625 0 0 1 5 15.375v-6.75A2.625 2.625 0 0 1 7.625 6");
}

</style>
