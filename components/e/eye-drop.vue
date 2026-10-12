<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uuiq1ab6y"/><path class="c14rvj8ns"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:eye-drop" /></template>
<style>
.c14rvj8ns {
  d: path("M12 15.25a1.75 1.75 0 1 1 0 3.5a1.75 1.75 0 1 1 0-3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uuiq1ab6y {
  d: path("M12 2.75c1.25 1.75 2.75 3.25 2.75 5a2.75 2.75 0 0 1-5.5 0c0-1.75 1.5-3.25 2.75-5M2.75 17c2.5-3 5.75-4.25 9.25-4.25S18.75 14 21.25 17c-2.5 3-5.75 4.25-9.25 4.25S5.25 20 2.75 17");
}

</style>
