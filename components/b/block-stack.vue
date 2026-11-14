<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="w4ox34bti"/><path class="b81ucwutr"/><path class="jdhxp6r5x"/><path class="og5qzjlhn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:block-stack" /></template>
<style>
.b81ucwutr {
  d: path("m8 4.25l4 2.25l4-2.25M12 6.5V11m-5 1.5l4 2.25v4.5L7 21.5l-4-2.25v-4.5Z");
}

.jdhxp6r5x {
  d: path("M3 14.75L7 17l4-2.25M7 17v4.5m10-9l4 2.25v4.5l-4 2.25l-4-2.25v-4.5Z");
}

.og5qzjlhn {
  d: path("M13 14.75L17 17l4-2.25M17 17v4.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.w4ox34bti {
  d: path("m12 2l4 2.25v4.5L12 11L8 8.75v-4.5Z");
}

</style>
