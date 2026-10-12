<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kr-inu18l"/><path class="wrqsbcbbe"/><path class="i6-vplb0c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bladder-sharp" /></template>
<style>
.i6-vplb0c {
  d: path("M7.75 14h8.5c-.5 2.25-2 3.5-4.25 3.5S8.25 16.25 7.75 14Z");
}

.kr-inu18l {
  d: path("M7 8.25L4.875 6.125L5.25 2.75M17 8.25l2.125-2.125l-.375-3.375M12 20v1.25");
}

.wrqsbcbbe {
  d: path("M12 6.75c4 0 7 2.75 7 6.5c0 4-3 6.75-7 6.75s-7-2.75-7-6.75c0-3.75 3-6.5 7-6.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
