<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="wvf93_btz"/><path class="ahhqo1b4s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heart-off-sharp-duotone" /></template>
<style>
.ahhqo1b4s {
  d: path("M1.7071 1.7071L22.2929 22.2929");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wvf93_btz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M3.54 3.5401L17.6427 17.6427C16.0253 19.0451 14.2253 20.4148 12.6494 21.7607C12.4624 21.9204 12.2312 22.0001 12 22.0001C11.9422 22.0001 11.8843 22.0001 11.8271 21.9901C11.6558 21.9554 11.4908 21.8804 11.3506 21.7607C9.1622 19.8917 6.5418 17.9769 4.5781 15.9922C2.582 13.9747 1 11.6443 1 8.75C1 6.6397 2 4.7758 3.54 3.5401ZM19.5165 15.9991L5.9975 2.307C6.6381 2.108 7.3117 2 8 2C9.4261 2 10.8308 2.479 12 3.2539C13.172 2.4608 14.5149 2.0001 16 2.0001C19.8256 2.0001 23 4.9823 23 8.75C23 11.0732 21.98 13.0331 20.5462 14.7594Z");
  stroke: none;
}

</style>
