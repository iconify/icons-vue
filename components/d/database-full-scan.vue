<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgmpl1v-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:database-full-scan" /></template>
<style>
.sgmpl1v-w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 4.999Q2.751 1.75 9.5 1.75q2.635 0 4.531.79Q16.25 3.464 16.25 5v8.426q-.821.245-1.5.831v-1.165Q13.068 14 9.5 14t-5.25-.908V16.5q0 1.75 5.25 1.75q2.457 0 3.764-.383q.059.762.366 1.421q-1.585.462-4.13.462q-6.75 0-6.75-3.25zm12 5.751V7.342q-1.682.908-5.25.908t-5.25-.908v3.408q0 1.75 5.25 1.75t5.25-1.75m2.75 3.75q-3 0-3 3t3 3q.97 0 1.626-.313l1.344 1.343q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-1.343-1.344q.313-.656.313-1.626q0-3-3-3m0 4.5Q16 19 16 17.5t1.5-1.5t1.5 1.5t-1.5 1.5");
}

</style>
