<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wyfqgbcbf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baby-budget" /></template>
<style>
.wyfqgbcbf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 5.5v-.75Q6.5 2 9.25 2T12 4.75v.75h2.25q.828 0 1.414.586T16.25 7.5q0 .765-.5 1.324v4.323q-.806.198-1.5.666V9.5h-10V19q0 .725.513 1.237q.512.513 1.237.513h6.5q.159 0 .304-.014q.281.42.66.8q.264.263.548.479q-.639.235-1.512.235H6q-1.346 0-2.298-.952T2.75 19V9q-.5-.5-.5-1.5q0-2 2-2zm1.5 0v-.75Q8 3.5 9.25 3.5t1.25 1.25v.75zm9 8.75q-3.75 0-3.75 3.75T17 21.75h2q3.75 0 3.75-3.75T19 14.25zM14.75 18q0-2.25 2.25-2.25T19.25 18T17 20.25T14.75 18m6.5 0q0 1.371-.835 1.906q.335-.785.335-1.906t-.335-1.906q.835.535.835 1.906");
}

</style>
