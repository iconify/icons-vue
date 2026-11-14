<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="lr1np3bum"/><path class="hqpnb7b7t"/><path class="hn8qjl2lr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:back-soon-sign" /></template>
<style>
.hn8qjl2lr {
  d: path("M12 12.25V14l1.25 1");
}

.hqpnb7b7t {
  d: path("M9 14a3 3 0 1 0 6 0a3 3 0 1 0-6 0Z");
}

.lr1np3bum {
  d: path("M4.5 8h15v12h-15ZM9 3.5V8m6-4.5V8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
