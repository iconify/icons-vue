<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9wkqlb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:block-defend" /></template>
<style>
.h9wkqlb6l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.25 15V7q0-2.25 2.25-2.25q.4 0 .75.121V4.5q0-2.25 2.25-2.25q.535 0 .942.127Q9.908 1.25 11.5 1.25q2.162 0 2.247 2.077q.338-.077.753-.077q2.25 0 2.25 2.25v6.833q-1.644.283-2.889 1.528q-1.611 1.611-1.611 3.889q0 1.8 1.006 3.183q-1.459.817-3.256.817q-2.796 0-4.773-1.977T3.25 15m10.25 2.75q0-1.76 1.245-3.005T17.75 13.5t3.005 1.245T22 17.75t-1.245 3.005T17.75 22t-3.005-1.245T13.5 17.75m1.5 0q0 2.75 2.75 2.75t2.75-2.75T17.75 15T15 17.75m1.254-.155q.031-.555.291-.881q-.113.454-.291.881");
}

</style>
