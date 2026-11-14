<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uuheekb4r"/><path class="clfxc-bak"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:intercity-train" /></template>
<style>
.clfxc-bak {
  d: path("M5.5 15.5a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m8 0a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m-11 4.25h19");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uuheekb4r {
  d: path("M2.5 14V6.5A1.5 1.5 0 0 1 4 5h9c4.5 0 8.5 4 8.5 9ZM5 8.5h10");
}

</style>
