<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="srl0e6big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:caret-up-circle" /></template>
<style>
.srl0e6big {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752m8.989 4.942l1.334 1.631q.902 1.102.292 2.389Q14.759 15 13.335 15h-2.67q-1.424 0-2.033-1.286q-.61-1.287.292-2.389l1.335-1.631q.675-.825 1.741-.825t1.741.825");
}

</style>
