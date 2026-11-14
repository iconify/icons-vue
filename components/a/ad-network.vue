<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p-h94obnd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ad-network" /></template>
<style>
.p-h94obnd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 5q0-3.25 3.25-3.25T8.25 5q0 1.095-.369 1.821l1.912 1.911Q10.655 8.25 12 8.25t2.207.482l1.912-1.911Q15.75 6.095 15.75 5q0-3.25 3.25-3.25T22.25 5T19 8.25q-1.095 0-1.821-.369l-1.911 1.912q.482.862.482 2.207t-.482 2.207l1.911 1.912q.726-.369 1.821-.369q3.25 0 3.25 3.25T19 22.25T15.75 19q0-1.095.369-1.821l-1.912-1.911q-.862.482-2.207.482t-2.207-.482l-1.912 1.911q.369.726.369 1.821q0 3.25-3.25 3.25T1.75 19T5 15.75q1.095 0 1.821.369l1.911-1.912Q8.25 13.345 8.25 12t.482-2.207L6.821 7.881Q6.095 8.25 5 8.25Q1.75 8.25 1.75 5");
}

</style>
