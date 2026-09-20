<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bkc3uob4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-row-above-rounded" /></template>
<style>
.bkc3uob4b {
  fill: currentColor;
  d: path("M11.643 7.856Q11.5 7.713 11.5 7.5V6H10q-.213 0-.356-.144T9.5 5.499t.144-.356T10 5h1.5V3.5q0-.213.144-.356T12.001 3t.356.144t.143.356V5H14q.213 0 .356.144t.144.357t-.144.356T14 6h-1.5v1.5q0 .213-.144.356T11.999 8t-.356-.144M5.616 21q-.667 0-1.141-.475T4 19.386v-5.943h16v5.943q0 .666-.475 1.14t-1.14.475zM4 12.442V6.616q0-.667.475-1.141T5.615 5h1.043q.2 0 .332.146q.131.146.126.354q0 2.027 1.42 3.456Q9.959 10.385 12 10.385t3.464-1.43q1.42-1.428 1.42-3.455q0-.2.128-.35t.33-.15h1.043q.666 0 1.14.474T20 6.616v5.826z");
}

</style>
