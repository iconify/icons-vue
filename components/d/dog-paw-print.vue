<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="npuv_nbvg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dog-paw-print" /></template>
<style>
.npuv_nbvg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 6q0-3.5 2.75-3.5T11.25 6T8.5 9.5T5.75 6m9.75-3.5q-2.75 0-2.75 3.5t2.75 3.5T18.25 6T15.5 2.5M4 8.75q-2.75 0-2.75 3.25q0 1.894.934 2.684q.669.566 1.816.566q2.75 0 2.75-3.25T4 8.75M17.25 12q0-3.25 2.75-3.25T22.75 12T20 15.25T17.25 12M12 11.25q2.178 0 4.494 2.559q2.256 2.494 2.256 4.691q0 3.25-3.75 3.25q-.592 0-1.682-.272q-.91-.228-1.318-.228t-1.318.228q-1.09.272-1.682.272q-3.75 0-3.75-3.25q0-2.197 2.256-4.691Q9.822 11.25 12 11.25");
}

</style>
