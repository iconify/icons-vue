<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f9nj0x_lo"/><path class="xz79xsboy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:magic-hat-rabbit" /></template>
<style>
.f9nj0x_lo {
  d: path("M8.748 11.5h6.504a1.5 1.5 0 0 1 1.482 1.728l-.468 3.044A1.5 1.5 0 0 0 17.748 18h.502a1.25 1.25 0 0 1 1.25 1.25a1.25 1.25 0 0 1-1.25 1.25H5.75a1.25 1.25 0 0 1-1.25-1.25A1.25 1.25 0 0 1 5.75 18h.502a1.5 1.5 0 0 0 1.482-1.728l-.468-3.044A1.5 1.5 0 0 1 8.748 11.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xz79xsboy {
  d: path("M8.611 3.622za1.5 1.5 0 0 1 1.737 1.216l.869 4.924A1.5 1.5 0 0 1 10 11.5a1.5 1.5 0 0 1-1.738-1.217l-.868-4.924a1.5 1.5 0 0 1 1.217-1.737m6.778 0za1.5 1.5 0 0 1 1.217 1.737l-.868 4.924A1.5 1.5 0 0 1 14 11.5a1.5 1.5 0 0 1-1.217-1.738l.869-4.924a1.5 1.5 0 0 1 1.737-1.216M7.5 14.75h9");
}

</style>
