<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="waqaemb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:database-query" /></template>
<style>
.waqaemb_b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 5.5Q2 2 9.75 2t7.75 3.5v7.75q-1.76 0-3.005 1.245l-.01.009Q12.666 15 9.75 15q-4.34 0-6.25-1.098V17.5q0 .628 1.574 1.246q1.919.754 4.676.754q2.142 0 3.777-.454q.309.8.965 1.457Q12.672 21 9.75 21Q2 21 2 17.5zm14 6V7.902Q14.09 9 9.75 9T3.5 7.902V11.5q0 .628 1.574 1.246q1.919.754 4.676.754t4.676-.754Q16 12.128 16 11.5m1.5 3q-3 0-3 3t3 3q.97 0 1.626-.313l1.344 1.343q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-1.343-1.344q.313-.656.313-1.626q0-3-3-3m0 4.5Q16 19 16 17.5t1.5-1.5t1.5 1.5t-1.5 1.5m-.25-1.5q0 .245.24.25q.01-.123.01-.25v-.25q-.25 0-.25.25");
}

</style>
