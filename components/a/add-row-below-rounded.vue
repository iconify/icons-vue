<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="to-m2s4ao"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-row-below-rounded" /></template>
<style>
.to-m2s4ao {
  fill: currentColor;
  d: path("M11.643 20.856q-.143-.143-.143-.356V19H10q-.213 0-.356-.144t-.144-.357t.144-.356T10 18h1.5v-1.5q0-.213.144-.356t.357-.144t.356.144t.143.356V18H14q.213 0 .356.144t.144.357t-.144.356T14 19h-1.5v1.5q0 .213-.144.356t-.357.144t-.356-.144M4 10.558V4.616q0-.667.475-1.141T5.615 3h12.77q.666 0 1.14.475T20 4.615v5.943zM5.616 19q-.667 0-1.141-.475T4 17.386v-5.827h16v5.827q0 .666-.475 1.14t-1.14.475h-1.043q-.2 0-.332-.146q-.131-.146-.126-.354q0-2.027-1.42-3.456q-1.422-1.429-3.464-1.429t-3.463 1.43Q7.116 16.472 7.116 18.5q0 .2-.128.35t-.33.15z");
}

</style>
