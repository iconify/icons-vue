<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="zyqtymbko"/><path class="dspu3053v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dead-letter" /></template>
<style>
.dspu3053v {
  d: path("m2.5 7l9.5 6l9.5-6m-6 8.5l5 5m0-5l-5 5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zyqtymbko {
  d: path("M12.6 19.5H2.5v-15h19v8.1");
}

</style>
