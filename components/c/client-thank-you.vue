<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="r6238w_3h"/><path class="r9eoyh5-b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:client-thank-you" /></template>
<style>
.r6238w_3h {
  d: path("M12.7 19.5H2.5v-15h19V13");
}

.r9eoyh5-b {
  d: path("m3.5 6l8.5 6.5L20.5 6M18 21l-2.75-2.75A2 2 0 0 1 18 15.5a2 2 0 0 1 2.75 2.75Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
