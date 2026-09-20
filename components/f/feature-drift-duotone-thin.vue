<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ydrfk9w6p"/><path class="x3nc7ebxq"/><path class="mpjdm200q"/><path class="qrn866ncb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:feature-drift-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mpjdm200q {
  d: path("M6 4v16");
}

.qrn866ncb {
  d: path("m10 9 3 3 3 -3 3 3");
}

.x3nc7ebxq {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("m10 9 3 3 3 -3 3 3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ydrfk9w6p {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M6 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
