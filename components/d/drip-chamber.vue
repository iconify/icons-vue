<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="kbs5sybai"/><rect class="zccsj6btr"/><path class="c3w7b1f4a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:drip-chamber" /></template>
<style>
.c3w7b1f4a {
  d: path("M12 7.75c.75 1 1.5 1.8 1.5 2.7a1.5 1.5 0 0 1-3 0c0-.9.75-1.7 1.5-2.7M7.75 14.5h8.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kbs5sybai {
  d: path("M12 2.75v3m0 11.5v4");
}

.zccsj6btr {
  width: 8.5px;
  height: 11.5px;
  x: 7.75px;
  y: 5.75px;
  rx: 2.5px;
}

</style>
