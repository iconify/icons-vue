<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lhf3anjcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:churro-sharp" /></template>
<style>
.lhf3anjcd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8.75 14.25l-3.6-9.5a1.625 1.625 0 0 1 3.25 0a1.625 1.625 0 0 1 3.25 0l3.6 9.5Zm3.25 0l-3.6-9.5m-.9 9.5h10.25l-.22 1.23l-.81 4.54l-.22 1.23h-9l-.22-1.23l-.81-4.54l-.22-1.23z");
}

</style>
