<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ojgy6j2ar"/><path class="nob-zobpu"/><path class="ew7yct7mp"/><path class="fy3uccb7z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:car-seat-pet" /></template>
<style>
.ew7yct7mp {
  d: path("M8.25 6a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0");
}

.fy3uccb7z {
  d: path("M9.25 3.5C6.75 2.75 5.5 4.75 6.5 7.25m8.25-3.75c2.5-.75 3.75 1.25 2.75 3.75M12 7h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nob-zobpu {
  d: path("M9.75 9H9a2 2 0 0 0-2 2v7.5h10V11a2 2 0 0 0-2-2h-.75");
}

.ojgy6j2ar {
  d: path("M4 14v5.5a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V14");
}

</style>
