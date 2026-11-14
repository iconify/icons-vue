<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ztmta2blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cheese-holes" /></template>
<style>
.ztmta2blw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 16.25v-3.586q0-1.662 1.533-2.306l13.61-5.707q1.167-.489 2.253.162l.89.534q1.214.728 1.214 2.144v8.759q0 1.036-.732 1.768t-1.768.732H4.75q-1.036 0-1.768-.732T2.25 16.25M13 12.5q0 2.5 2.5 2.5t2.5-2.5t-2.5-2.5t-2.5 2.5m-5 0q-2 0-2 2t2 2t2-2t-2-2");
}

</style>
