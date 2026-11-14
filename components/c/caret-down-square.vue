<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yle5iwrsh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:caret-down-square" /></template>
<style>
.yle5iwrsh {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.375 2.75h-4.75q-2.848 0-4.861 2.014T2.75 9.625v4.75q0 2.848 2.014 4.861t4.861 2.014h4.75q2.848 0 4.861-2.014t2.014-4.861v-4.75q0-2.848-2.014-4.861T14.375 2.75m-4.116 11.556l-1.334-1.631q-.902-1.102-.292-2.389Q9.241 9 10.665 9h2.67q1.424 0 2.033 1.286q.61 1.287-.292 2.389l-1.335 1.631q-.675.825-1.741.825t-1.741-.825");
}

</style>
