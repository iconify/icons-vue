<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eoz-qosvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:insulin-pump" /></template>
<style>
.eoz-qosvf {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2.25h5.5q1.76 0 3.005 1.245T15.75 6.5v3q0 1.76-1.245 3.005q-.792.793-1.794 1.081q-.256 1.908-2.197 3.548Q9.25 18.203 9.25 19q0 .981 1.646 1.096q2.062.143 3.913-1.203q.109-.079.24-.115Q15 18.413 15 18q0-3.5 3.5-3.5T22 18t-3.5 3.5q-2.123 0-2.958-1.287q-2.228 1.555-4.75 1.379Q7.75 21.38 7.75 19q0-1.493 1.796-3.011q1.288-1.089 1.602-2.239H6q-1.76 0-3.005-1.245T1.75 9.5v-3q0-1.76 1.245-3.005T6 2.25m5 2.5H6.5Q4.25 4.75 4.25 7v1q0 2.25 2.25 2.25H11q.932 0 1.591-.659T13.25 8V7q0-.932-.659-1.591T11 4.75");
}

</style>
