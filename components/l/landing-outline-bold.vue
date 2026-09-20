<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="m8ek3-bfo"/><path class="eisa2cb9u"/><path class="o7l5jxuid"/><path class="hmmgrhbhr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:landing-outline-bold" /></template>
<style>
.eisa2cb9u {
  d: path("M2 22h20");
}

.hmmgrhbhr {
  d: path("M2 5h3V2");
}

.m8ek3-bfo {
  d: path("m12 3 2 2v4l5.5 5.5H14V17l2 2H8l2 -2v-2.5H4.5L10 9V5Z");
}

.o7l5jxuid {
  d: path("m2 2 3 3");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
