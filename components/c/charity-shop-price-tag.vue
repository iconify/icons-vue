<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jghc952xt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:charity-shop-price-tag" /></template>
<style>
.jghc952xt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.913 2H5.375Q2 2 2 5.375v3.538q0 1.398.989 2.386l4.625 4.625q2.386 2.386 4.772 0l3.538-3.538q2.386-2.386 0-4.772l-4.625-4.625Q10.311 2 8.913 2M4.75 7q0-2.25 2.25-2.25T9.25 7T7 9.25T4.75 7m13.197 15.007l-2.75-3q-.098-.107-.149-.243q-.656-1.747.725-3.002q1.243-1.13 2.727-.578q1.484-.552 2.727.578q1.381 1.255.725 3.002q-.051.136-.149.243l-2.75 3q-.05.054-.11.098q-.059.044-.126.075t-.139.049q-.072.017-.145.02q-.074.004-.147-.008q-.073-.011-.143-.036q-.069-.026-.132-.064t-.118-.088q-.024-.022-.046-.046m2.643-3.897q.205-.713-.372-1.238q-.627-.57-1.389-.198q-.077.037-.16.057q-.083.019-.169.019t-.169-.019q-.083-.02-.16-.057q-.762-.372-1.389.198q-.577.525-.372 1.238l2.09 2.28z");
}

</style>
