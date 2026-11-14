<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lt46w2bum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bank-hours" /></template>
<style>
.lt46w2bum {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.811 6.75h.689q1.76 0 3.005 1.245T21.75 11v7q0 1.76-1.245 3.005T17.5 22.25h-11q-1.76 0-3.005-1.245T2.25 18v-7q0-1.76 1.245-3.005T6.5 6.75h.689l4.28-4.28h.001q.105-.106.243-.163T12 2.25h.01q.087 0 .171.02t.163.058q.078.039.145.095q.067.055.119.124zm-2.122 0L12 4.061L9.311 6.75zm-6.225 4.214Q7 12.429 7 14.5t1.464 3.536Q9.929 19.5 12 19.5t3.536-1.464Q17 16.571 17 14.5t-1.464-3.536T12 9.5t-3.536 1.464");
}

</style>
