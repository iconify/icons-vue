<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e1rlcc78l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-row-above" /></template>
<style>
.e1rlcc78l {
  fill: currentColor;
  d: path("M4 21v-7.558h16V21zm0-8.558V5h3.139q-.012.125-.018.244t-.005.256q0 2.027 1.42 3.456Q9.959 10.385 12 10.385t3.464-1.43q1.42-1.428 1.42-3.455q0-.138-.005-.256T16.86 5H20v7.442zM11.5 8V6h-2V5h2V3h1v2h2v1h-2v2z");
}

</style>
