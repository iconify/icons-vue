<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d5qpb19oi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:claim-inspection" /></template>
<style>
.d5qpb19oi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m2.483 9.457l3.25-3.249Q7.5 4.441 9.267 6.206l3.25 3.251q.733.732.733 1.768v.534q.116-.135.245-.264Q14.74 10.25 16.5 10.25t3.005 1.245T20.75 14.5q0 1.373-.757 2.432l1.537 1.538q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-1.538-1.537q-1.059.757-2.432.757q-1.76 0-3.005-1.245q-.206-.206-.378-.426q-.18.519-.599.939q-.732.732-1.768.732h-6.5q-1.036 0-1.768-.732T1.75 16.25v-5.025q0-1.036.733-1.768");
}

</style>
