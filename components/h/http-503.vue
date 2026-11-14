<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e_1_mtyjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:http-503" /></template>
<style>
.e_1_mtyjt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 2.5h12.5a3.25 3.25 0 0 1 3.25 3.25A3.25 3.25 0 0 1 18.25 9H5.75A3.25 3.25 0 0 1 2.5 5.75A3.25 3.25 0 0 1 5.75 2.5m5.75 16H5.75q-.16 0-.319-.016q-.158-.015-.315-.046q-.157-.032-.309-.078q-.153-.046-.301-.107q-.147-.061-.288-.137q-.141-.075-.274-.164q-.132-.088-.256-.19q-.123-.101-.236-.214t-.214-.236t-.19-.256t-.164-.274t-.137-.288q-.061-.148-.107-.301q-.046-.152-.078-.309q-.031-.157-.046-.315q-.016-.159-.016-.319t.016-.319q.015-.158.046-.315q.032-.157.078-.309q.046-.153.107-.301q.061-.147.137-.288q.075-.141.164-.274q.088-.132.19-.256q.101-.123.214-.236t.236-.214q.124-.102.256-.19q.133-.089.274-.164t.288-.137q.148-.061.301-.107q.152-.046.309-.078q.157-.031.315-.046Q5.59 12 5.75 12h9.6M6 5.75h.01M6 15.25h.01M14.25 18a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0m2 0h3.5");
}

</style>
