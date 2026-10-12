<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v9d69j5xl"/><path class="wzqh5rujp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dice-d20" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v9d69j5xl {
  d: path("m13.3 3.5l5.4 3.13q1.3.75 1.3 2.25v6.25q0 1.5-1.3 2.25l-5.4 3.12q-1.3.75-2.6 0l-5.4-3.12Q4 16.63 4 15.13V8.88q0-1.5 1.3-2.25l5.4-3.13q1.3-.75 2.6 0");
}

.wzqh5rujp {
  d: path("m12.38 8.14l3.99 6.72q.38.64-.37.64H8q-.75 0-.37-.64l3.99-6.72q.38-.64.76 0M12 7.5v-4m-4.75 12L4.6 17m12.15-1.5L19.4 17");
}

</style>
