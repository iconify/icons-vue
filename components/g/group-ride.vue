<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hv36rbz-q"/><path class="ixgqoizyo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:group-ride" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hv36rbz-q {
  d: path("M2.5 11A3.25 3.25 0 1 0 9 11a3.25 3.25 0 1 0-6.5 0m16.997.14q.003-.07.003-.14q0-.16-.016-.319q-.015-.158-.046-.315q-.032-.157-.078-.309q-.046-.153-.107-.301q-.061-.147-.137-.288q-.075-.141-.164-.274q-.088-.132-.19-.256q-.101-.123-.214-.236t-.236-.214q-.124-.102-.256-.19q-.133-.089-.274-.164t-.288-.137q-.148-.061-.301-.107q-.152-.046-.309-.078q-.157-.031-.315-.046q-.159-.016-.319-.016t-.319.016q-.158.015-.315.046q-.157.032-.309.078q-.153.046-.301.107q-.147.061-.288.137q-.141.075-.274.164q-.132.088-.256.19q-.123.101-.236.214t-.214.236q-.102.124-.19.256q-.089.133-.164.274t-.137.288q-.061.148-.107.301q-.046.152-.078.309q-.031.157-.046.315Q13 10.84 13 11q0 .308.058.611q.058.302.172.589q.113.286.279.546t.377.484");
}

.ixgqoizyo {
  d: path("M5.75 11h4.75l3.25-5.5H9l1.5 5.5m3.25-5.5l2.5 5.5m-2.5-5.5l-.5-2h2.25m.5 12.25a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-1.75 6c0-1.75 1.75-3 3.75-3s3.75 1.25 3.75 3");
}

</style>
