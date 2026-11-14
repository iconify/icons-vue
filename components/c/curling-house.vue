<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ncn5is-qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:curling-house" /></template>
<style>
.ncn5is-qa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12M5 12q-.001 2.9 2.049 4.951Q9.1 19.002 12 19.002t4.951-2.051Q19.001 14.9 19 12q.001-2.9-2.049-4.951Q14.9 4.998 12 4.998T7.049 7.049T5 12");
}

</style>
