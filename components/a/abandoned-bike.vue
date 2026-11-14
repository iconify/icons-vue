<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="o2w3mia0h"/><path class="xh3xvwbsy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:abandoned-bike" /></template>
<style>
.o2w3mia0h {
  d: path("M2.5 8.75a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Zm15.733.329q.017-.164.017-.329q0-.16-.016-.319q-.015-.158-.046-.315q-.032-.157-.078-.309q-.046-.153-.107-.301q-.061-.147-.137-.288q-.075-.141-.164-.274q-.088-.132-.19-.256q-.101-.123-.214-.236t-.236-.214t-.256-.19t-.274-.164t-.288-.137q-.148-.061-.301-.107q-.152-.046-.309-.078q-.157-.031-.315-.046Q15.16 5.5 15 5.5t-.319.016q-.158.015-.315.046q-.157.032-.309.078q-.153.046-.301.107q-.147.061-.288.137q-.141.075-.274.164q-.132.088-.256.19q-.123.101-.236.214t-.214.236q-.102.124-.19.256q-.089.133-.164.274t-.137.288q-.061.148-.107.301q-.046.152-.078.309q-.031.157-.046.315q-.016.159-.016.319t.016.319q.015.158.046.315q.032.157.078.309q.046.153.107.301q.061.147.137.288q.075.141.164.274q.088.132.19.256q.101.123.214.236t.236.214q.124.102.256.19q.133.089.274.164t.288.137q.148.061.301.107q.152.046.309.078q.157.031.315.046Q14.84 12 15 12q.719 0 1.37-.303");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xh3xvwbsy {
  d: path("M5.75 8.75h4.5l-2-5.25m2 5.25l3-5.25L15 8.75M8.25 3.5h5m1 18l3.75-7l3.75 7Zm3.75-4v1.75");
}

</style>
