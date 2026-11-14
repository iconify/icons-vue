<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yp5ss34ob"/><path class="me83ptjee"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:address-book-pin" /></template>
<style>
.me83ptjee {
  d: path("M12.5 17s-3.75-3-3.75-6a3.75 3.75 0 0 1 7.5 0c0 3-3.75 6-3.75 6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yp5ss34ob {
  d: path("M5.5 2.5h14v19h-14Zm-2 5h2m-2 4.5h2m-2 4.5h2");
}

</style>
