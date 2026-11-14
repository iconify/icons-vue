<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxjknts0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:caret-right-circle" /></template>
<style>
.cxjknts0h {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752m9.554 8.989l-1.631 1.334q-1.102.902-2.389.292Q9 14.759 9 13.335v-2.67q0-1.424 1.286-2.033q1.287-.61 2.389.292l1.631 1.335q.825.675.825 1.741t-.825 1.741");
}

</style>
