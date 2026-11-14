<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxyx-8bsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cat-bed" /></template>
<style>
.bxyx-8bsy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 10.499q.001-2.523 3.183-4.198Q7.88 4.75 12 4.75t7.067 1.551Q22.25 7.976 22.25 10.5v3q0 2.524-3.183 4.199Q16.12 19.25 12 19.25t-7.067-1.551Q1.75 16.024 1.75 13.5zM6.25 10q0 2.5 5.75 2.5t5.75-2.5T12 7.5T6.25 10m-2.999 3.566q.048 1.578 2.381 2.806Q8.25 17.75 12 17.75t6.368-1.378q2.333-1.228 2.381-2.806q-.685.608-1.682 1.133Q16.12 16.25 12 16.25t-7.067-1.551q-.997-.525-1.682-1.133");
}

</style>
