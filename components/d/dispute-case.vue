<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9lv2g89l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dispute-case" /></template>
<style>
.w9lv2g89l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.146 4.257l4.597 4.597a1.75 1.75 0 0 1 0 2.474l-1.415 1.415a1.75 1.75 0 0 1-2.474 0l-4.597-4.597a1.75 1.75 0 0 1 0-2.474l1.415-1.415a1.75 1.75 0 0 1 2.474 0M12.5 10.5L4 19m8-2.25h8a1.5 1.5 0 0 1 1.5 1.5a1.5 1.5 0 0 1-1.5 1.5h-8a1.5 1.5 0 0 1-1.5-1.5a1.5 1.5 0 0 1 1.5-1.5");
}

</style>
