<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rb-djacal"/><path class="czkpr2bld"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cardigan" /></template>
<style>
.czkpr2bld {
  d: path("m8.5 3l3.5 7.5L15.5 3M12 13.25h.01M12 16h.01M12 18.75h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rb-djacal {
  d: path("m8.5 3l-4 1.5C3.5 4.83 3 5.75 3 6.75V21.5h18V6.75c0-1-.5-1.92-1.5-2.25l-4-1.5");
}

</style>
