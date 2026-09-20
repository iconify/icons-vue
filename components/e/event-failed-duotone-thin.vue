<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ebovp7bpp"/><path class="c000x0vfn"/><path class="wbs7q7b-t"/><path class="v-jogvb5z"/><path class="weeetziwb"/><path class="qydoy8byr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:event-failed-duotone-thin" /></template>
<style>
.c000x0vfn {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m14 10 5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ebovp7bpp {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 6 -5 5h4l-5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qydoy8byr {
  d: path("m19 10 -5 5");
}

.v-jogvb5z {
  d: path("m10 6 -5 5h4l-5 5");
}

.wbs7q7b-t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m19 10 -5 5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.weeetziwb {
  d: path("m14 10 5 5");
}

</style>
