<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ui-j59bdb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:kohl-surma" /></template>
<style>
.ui-j59bdb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.5 4.75h3a.75.75 0 0 1 0 1.5h-.25v5.1c2.1.75 3.5 2.6 3.5 4.9c0 2.75-2 4.75-4.75 4.75s-4.75-2-4.75-4.75c0-2.3 1.4-4.15 3.5-4.9v-5.1h-.25a.75.75 0 0 1 0-1.5m2.25-.5l3.5-1.5");
}

</style>
