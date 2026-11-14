<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjwjzbckw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:colour-mixing-light" /></template>
<style>
.zjwjzbckw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.581 4.581Q5.75 6.411 5.75 9q0 .183.009.362q-.907.447-1.678 1.219Q2.25 12.411 2.25 15t1.831 4.419T8.5 21.25q1.969 0 3.5-1.059q1.531 1.059 3.5 1.059q2.589 0 4.419-1.831Q21.75 17.589 21.75 15t-1.831-4.419q-.771-.772-1.678-1.219q.009-.179.009-.362q0-2.589-1.831-4.419Q14.589 2.75 12 2.75T7.581 4.581");
}

</style>
