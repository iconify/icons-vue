<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k5u9j5b8v"/><rect class="h3mgs66ik"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bell-tower" /></template>
<style>
.h3mgs66ik {
  width: 10px;
  height: 3.25px;
  x: 7px;
  y: 18px;
  rx: 0.5px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k5u9j5b8v {
  d: path("m12.38 3.08l4.99 4.34q.38.33-.12.33H6.75q-.5 0-.12-.33l4.99-4.34q.38-.33.76 0M7 7.75V18M17 7.75V18M12 7.75v3.5M9.75 15h4.5c-1-.75-1-1.25-1-2.5a1.25 1.25 0 0 0-2.5 0c0 1.25 0 1.75-1 2.5");
}

</style>
