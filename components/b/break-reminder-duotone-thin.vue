<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="icnat23co"/><path class="s3r-7pbpm"/><path class="llew0ibxe"/><path class="zcykq5u6t"/><path class="r57e8zbzz"/><path class="ng_tlibuk"/><path class="s0v-_1bji"/><path class="v9hia4w8h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:break-reminder-duotone-thin" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.icnat23co {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M4 9v9h11V9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.llew0ibxe {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M7 3a3 3 0 0 1 0 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.ng_tlibuk {
  d: path("M15 9a3 3 0 0 1 0 6");
}

.r57e8zbzz {
  d: path("M4 9v9h11V9");
}

.s0v-_1bji {
  d: path("M7 3a3 3 0 0 1 0 6");
}

.s3r-7pbpm {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M15 9a3 3 0 0 1 0 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v9hia4w8h {
  d: path("M12 3a3 3 0 0 1 0 6");
}

.zcykq5u6t {
  stroke-width: var(--svg-stroke-width--4-5px, 4.5px);
  d: path("M12 3a3 3 0 0 1 0 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
