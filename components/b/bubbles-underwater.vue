<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm_1jx0za"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bubbles-underwater" /></template>
<style>
.bm_1jx0za {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8 4.5Q8 2 10.5 2T13 4.5T10.5 7T8 4.5m9 1.75q-3.25 0-3.25 3.25T17 12.75t3.25-3.25T17 6.25M3.25 15.5q0-2.175 1.538-3.712Q6.325 10.25 8.5 10.25t3.712 1.538q1.538 1.537 1.538 3.712t-1.538 3.712Q10.675 20.75 8.5 20.75t-3.712-1.538Q3.25 17.675 3.25 15.5");
}

</style>
