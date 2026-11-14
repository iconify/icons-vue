<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qc4tf17ws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:goal-owner" /></template>
<style>
.qc4tf17ws {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 10q0-3.417 2.416-5.834T10 1.75t5.834 2.416Q18.25 6.583 18.25 10q0 .777-.125 1.502q-.062-.002-.125-.002q-3.75 0-3.75 3.75q0 .966.249 1.684Q12.522 18.25 10 18.25q-3.417 0-5.834-2.416T1.75 10m4.891-3.359Q5.25 8.032 5.25 10t1.391 3.359T10 14.75t3.359-1.391T14.75 10t-1.391-3.359T10 5.25T6.641 6.641M15.5 15.25q0-2.5 2.5-2.5q1.036 0 1.768.732t.732 1.768t-.732 1.768T18 17.75q-2.5 0-2.5-2.5m1.5 0q0 1 1 1q.414 0 .707-.293T19 15.25t-.293-.707T18 14.25q-1 0-1 1M18 18q-4.25 0-4.25 3.25q0 1.25 1.25 1.25h6q1.25 0 1.25-1.25Q22.25 18 18 18m2.735 3h-5.47q.189-1.5 2.735-1.5t2.735 1.5");
}

</style>
