<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="spts5jbcu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cabinet-latch" /></template>
<style>
.spts5jbcu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17 1.75H7q-1.76 0-3.005 1.245T2.75 6v12q0 1.76 1.245 3.005T7 22.25h10q1.76 0 3.005-1.245T21.25 18V6q0-1.76-1.245-3.005T17 1.75m-7.5 8h5q2.25 0 2.25 2.25t-2.25 2.25h-5q-2.25 0-2.25-2.25T9.5 9.75");
}

</style>
