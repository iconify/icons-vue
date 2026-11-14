<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ug_up2tch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cash-stack" /></template>
<style>
.ug_up2tch {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 8.5h9.625q3.375 0 3.375 3.375V14H20q.75 0 .75-.75v-6q0-.75-.75-.75H7q-.75 0-.75.75zm13 7v.125Q19.25 19 15.875 19H5.125Q1.75 19 1.75 15.625v-3.75q0-1.398.989-2.386q.853-.854 2.011-.97V7.25Q4.75 5 7 5h13q2.25 0 2.25 2.25v6q0 .932-.659 1.591T20 15.5zm-8.75-4.25q-3.25 0-3.25 2.5t3.25 2.5q1.272 0 2.198-.648q1.052-.737 1.052-1.852t-1.052-1.852q-.926-.648-2.198-.648");
}

</style>
