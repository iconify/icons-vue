<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="itf9zfbyl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:copy-properties" /></template>
<style>
.itf9zfbyl {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 1.75h-4q-1.839 0-2.175 1.503q-1.648.059-2.83 1.242Q3.75 5.74 3.75 7.5V18q0 1.76 1.245 3.005T8 22.25h8q1.76 0 3.005-1.245T20.25 18V7.5q0-1.76-1.245-3.005q-1.199-1.199-2.876-1.243q-.161-.466-.538-.843Q14.932 1.75 14 1.75m-.409 8.781l1.378 1.378q.66.659.66 1.591t-.66 1.591l-1.378 1.378q-.659.66-1.591.66t-1.591-.66l-1.378-1.378q-.66-.659-.66-1.591t.66-1.591l1.378-1.378q.659-.66 1.591-.66t1.591.66");
}

</style>
