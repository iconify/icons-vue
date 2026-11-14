<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lo9-khxwj"/><path class="wo9jxxb_r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:leaf-cabbage" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lo9-khxwj {
  d: path("M12 21.25c-5.25 0-9.25-3.75-9.25-8.75c0-3.5 1.75-6.5 4.5-8q2.25 1 4.75-1q2.5 2 4.75 1c2.75 1.5 4.5 4.5 4.5 8c0 5-4 8.75-9.25 8.75");
}

.wo9jxxb_r {
  d: path("M12 21.25C6.5 18 6 10 10.25 7M12 21.25C17.5 18 18 10 13.75 7M12 21.25V11.5");
}

</style>
