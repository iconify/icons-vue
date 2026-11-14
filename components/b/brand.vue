<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ula25bbov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:brand" /></template>
<style>
.ula25bbov {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752m8.585 3.886l.283.849q.17.513.711.513h.966q1.022 0 1.37.961q.348.96-.437 1.615l-.764.637q-.368.307-.244.77l.253.949q.263.986-.572 1.574q-.836.587-1.675.005l-.801-.553q-.427-.296-.854 0l-.801.554q-.839.581-1.675-.006q-.835-.588-.572-1.575l.253-.948q.124-.463-.244-.77l-.764-.637q-.785-.655-.437-1.615Q7.681 10 8.703 10h.966q.541 0 .711-.513l.283-.849q.322-.963 1.337-.963t1.336.962z");
}

</style>
