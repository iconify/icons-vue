<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nh88xf_mg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:forbidden" /></template>
<style>
.nh88xf_mg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752m3.359.177l10.96 10.96q.66.659.66 1.591t-.66 1.592q-.659.659-1.591.659t-1.591-.66L4.929 8.111q-.66-.659-.66-1.591t.66-1.591q.659-.66 1.591-.66t1.591.66");
}

</style>
