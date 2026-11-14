<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gph6pkwhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:layout-panel-bottom" /></template>
<style>
.gph6pkwhw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.25 3.25h-8.5q-2.485 0-4.243 1.757Q1.75 6.765 1.75 9.25v5.5q0 2.485 1.757 4.243Q5.265 20.75 7.75 20.75h8.5q2.485 0 4.243-1.757q1.757-1.758 1.757-4.243v-5.5q0-2.485-1.757-4.243Q18.735 3.25 16.25 3.25m-9 9.5h9.5q1.036 0 1.768.732t.732 1.768t-.732 1.768t-1.768.732h-9.5q-2.5 0-2.5-2.5t2.5-2.5");
}

</style>
