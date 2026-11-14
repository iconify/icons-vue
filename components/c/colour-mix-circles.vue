<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qdi8bkb8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:colour-mix-circles" /></template>
<style>
.qdi8bkb8j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 9q0-2.589 1.831-4.419Q9.411 2.75 12 2.75t4.419 1.831T18.25 9q0 .183-.009.362q.907.447 1.678 1.219Q21.75 12.411 21.75 15t-1.831 4.419T15.5 21.25q-1.969 0-3.5-1.059q-1.531 1.059-3.5 1.059q-2.589 0-4.419-1.831Q2.25 17.589 2.25 15t1.831-4.419q.771-.772 1.678-1.219Q5.75 9.183 5.75 9");
}

</style>
