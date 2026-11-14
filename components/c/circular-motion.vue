<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dgy3l9kfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:circular-motion" /></template>
<style>
.dgy3l9kfz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m10.498 1.939l2.055 1.827q3.062.182 5.281 2.4Q20.25 8.583 20.25 12t-2.416 5.834T12 20.25q-1.059 0-2.023-.232Q11 18.846 11 17.25q0-1.76-1.245-3.005T6.75 13q-1.596 0-2.768 1.023Q3.75 13.059 3.75 12q0-3.417 2.416-5.834q1.842-1.841 4.265-2.279l-.929-.826q-.112-.1-.177-.234t-.074-.283t.04-.29t.148-.252q.05-.055.108-.1q.059-.045.126-.077q.066-.032.138-.051q.071-.018.145-.023q.074-.004.147.006t.143.034t.133.062q.064.037.119.086M3.75 17.25q0-3 3-3t3 3t-3 3t-3-3m1.5 0q0 1.5 1.5 1.5t1.5-1.5t-1.5-1.5t-1.5 1.5m1.5.25q-.25 0-.25-.25t.25-.25t.25.25t-.25.25");
}

</style>
