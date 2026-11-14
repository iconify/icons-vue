<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwzdsxbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-mapping" /></template>
<style>
.zwzdsxbvv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 3.5h2A1.5 1.5 0 0 1 7.5 5A1.5 1.5 0 0 1 6 6.5H4A1.5 1.5 0 0 1 2.5 5A1.5 1.5 0 0 1 4 3.5m0 7h2A1.5 1.5 0 0 1 7.5 12A1.5 1.5 0 0 1 6 13.5H4A1.5 1.5 0 0 1 2.5 12A1.5 1.5 0 0 1 4 10.5m0 7h2A1.5 1.5 0 0 1 7.5 19A1.5 1.5 0 0 1 6 20.5H4A1.5 1.5 0 0 1 2.5 19A1.5 1.5 0 0 1 4 17.5m14-14h2A1.5 1.5 0 0 1 21.5 5A1.5 1.5 0 0 1 20 6.5h-2A1.5 1.5 0 0 1 16.5 5A1.5 1.5 0 0 1 18 3.5m0 7h2a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-2a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5m0 7h2a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-2a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5M7.5 5l9 7m-9 0l9-7m-9 14h9");
}

</style>
