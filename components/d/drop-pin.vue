<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zrf39kblz"/><path class="et0lzmyju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:drop-pin" /></template>
<style>
.et0lzmyju {
  d: path("M13.5 9.25a1.5 1.5 0 1 1-3 0a1.5 1.5 0 1 1 3 0m-4.75-6.5v1m6.5-1v1M8.75 17.5c-3.4.35-6 1.1-6 1.9c0 1.05 4.15 1.85 9.25 1.85s9.25-.8 9.25-1.85c0-.8-2.6-1.55-6-1.9");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zrf39kblz {
  d: path("M12 17c-.25 0-.5-.1-.68-.27c-2.07-1.93-4.07-4.58-4.07-7.48a4.75 4.75 0 0 1 9.5 0c0 2.9-2 5.55-4.07 7.48c-.18.17-.43.27-.68.27");
}

</style>
