<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i4l-1cb6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:anointing-oil" /></template>
<style>
.i4l-1cb6d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.561 1.502Q14.75 3.965 14.75 5.25Q14.75 8 12 8T9.25 5.25q0-1.285 2.189-3.748q.05-.055.108-.1q.059-.045.126-.077q.066-.032.138-.051q.071-.018.145-.023q.074-.004.147.006t.143.034t.133.062q.064.037.119.086q.033.03.063.063M14.75 11q0-1.75-1.75-1.75h-2q-1.75 0-1.75 1.75q0 .935.5 1.371v.635q-1.928.933-2.551 3.074q-.698 2.399.802 4.398T12 22.476t3.999-1.998q1.5-1.999.802-4.398q-.623-2.141-2.551-3.074v-.635q.5-.436.5-1.371m-2 2.5q0 .114.034.223q.034.11.099.204t.155.164t.197.111q1.637.617 2.126 2.297q.488 1.679-.562 3.078T12 20.976t-2.799-1.399t-.562-3.078q.489-1.68 2.126-2.297q.107-.041.197-.111t.155-.164t.099-.204t.034-.223v-.75h1.5z");
}

</style>
