<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="j8bxj4b5o"/><path class="gtdkf60xt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:arrow-split" /></template>
<style>
.gtdkf60xt {
  d: path("M4.75 10.5V5.75H9.5m5 0h4.75v4.75");
}

.j8bxj4b5o {
  d: path("M12 21v-8L5 6m7 7l7-7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
