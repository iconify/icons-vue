<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mss9kqp9p"/><path class="qjli_3_xs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:funeral-candle-sharp" /></template>
<style>
.mss9kqp9p {
  d: path("M12 5V2.75M7.75 9c0-2.25 1.9-4 4.25-4s4.25 1.75 4.25 4m-9 1.5H17.5l-.11.74l-1.03 6.77l-.11.74h-8.5l-.11-.74l-1.03-6.77l-.11-.74z");
}

.qjli_3_xs {
  d: path("m12 12.5l1.25 1.583V15a1.25 1.25 0 0 1-2.5 0v-.917zm-5.25 8.75h10.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
