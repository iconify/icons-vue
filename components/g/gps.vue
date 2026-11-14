<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aram8cgud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:gps" /></template>
<style>
.aram8cgud {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m6.184-4.066Q6.25 9.618 6.25 12t1.684 4.066T12 17.75t4.066-1.684T17.75 12t-1.684-4.066T12 6.25T7.934 7.934");
}

</style>
