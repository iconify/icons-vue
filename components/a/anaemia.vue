<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r4ti6_d0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:anaemia" /></template>
<style>
.r4ti6_d0f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.398 4.028q-1.196-1.465-1.809-2.243q-.055-.069-.124-.124q-.058-.045-.124-.079t-.137-.054t-.145-.026q-.073-.005-.147.003q-.073.009-.143.032q-.071.022-.135.058t-.121.084q-.056.048-.102.106q-.613.777-1.809 2.243Q4 10.891 4 14.5q0 2.084.942 3.748Q6.474 22.25 12 22.25t7.058-4.002Q20 16.584 20 14.5q0-3.609-5.602-10.472");
}

</style>
