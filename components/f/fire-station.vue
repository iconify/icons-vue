<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ku2_1dw6p"/><path class="dayt1nhzk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fire-station" /></template>
<style>
.dayt1nhzk {
  d: path("M5 21.5V16q0-.16.016-.319q.015-.158.046-.315q.032-.157.078-.309q.046-.153.107-.301q.061-.147.137-.288q.075-.141.164-.274q.088-.132.19-.256q.101-.123.214-.236t.236-.214q.124-.102.256-.19q.133-.089.274-.164t.288-.137q.148-.061.301-.107q.152-.046.309-.078q.157-.031.315-.046q.159-.016.319-.016t.319.016q.158.015.315.046q.157.032.309.078q.153.046.301.107q.147.061.288.137q.141.075.274.164q.132.088.256.19q.123.101.236.214t.214.236q.102.124.19.256q.089.133.164.274t.137.288q.061.148.107.301q.046.152.078.309q.031.157.046.315q.016.159.016.319v2.45m0 .2v2.85m6.5.5c-2.25 0-3.75-1.5-3.75-3.5s1.75-3 2.25-5q1.5 1.5 1.5 3c.75-.5 1.25-1.25 1.5-2c1.5 1.25 2.25 2.5 2.25 4c0 2-1.5 3.5-3.75 3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ku2_1dw6p {
  d: path("M12.133 21.5H3V9l9-6l9 6v3.167");
}

</style>
