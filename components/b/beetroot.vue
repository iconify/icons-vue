<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ip9umh_bl"/><path class="hm6q_5uui"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beetroot" /></template>
<style>
.hm6q_5uui {
  d: path("M12 7.5c-4 0-6-2.25-5.5-4.25C10 3.25 12 5 12 7.5m0 0c4 0 6-2.25 5.5-4.25C14 3.25 12 5 12 7.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ip9umh_bl {
  d: path("M12 20.75C11 19 5.5 18.5 5.5 14a6.5 6.5 0 0 1 13 0c0 4.5-5.5 5-6.5 6.75");
}

</style>
