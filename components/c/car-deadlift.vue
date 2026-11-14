<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgmbun_pd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:car-deadlift" /></template>
<style>
.sgmbun_pd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 11v2.75H5.25V11q0-1.75-1.75-1.75T1.75 11v7q0 1.75 1.75 1.75T5.25 18v-2.75h13.5V18q0 1.75 1.75 1.75T22.25 18v-7q0-1.75-1.75-1.75T18.75 11v2.75H17.5V11q0-1.979-1.742-2.217l-1.319-3.078q-.043-.102-.114-.186q-.07-.085-.162-.145q-.092-.061-.197-.092q-.106-.032-.216-.032h-3.5q-.11 0-.216.032q-.105.031-.197.092q-.092.06-.162.145t-.114.186L8.242 8.783Q6.5 9.021 6.5 11m9.5 2.75H8V11q0-.75.75-.75q.11 0 .216-.032q.105-.031.197-.092q.092-.06.162-.145t.114-.186l1.306-3.045h2.51l1.306 3.045q.043.102.114.186q.07.085.162.145q.092.061.197.092q.106.032.216.032q.75 0 .75.75z");
}

</style>
