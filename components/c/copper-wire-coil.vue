<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f562tbxqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:copper-wire-coil" /></template>
<style>
.f562tbxqe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.838 5.446Q1.75 7.722 1.75 11t3.088 5.554Q7.818 18.75 12 18.75q3.704 0 6.467-1.724l1.879 3.342q.037.064.085.12t.106.102t.124.079t.137.053t.145.026q.073.005.147-.003q.073-.009.143-.032t.135-.059t.12-.085q.056-.048.102-.106t.079-.124t.053-.137t.026-.145q.005-.073-.003-.147q-.009-.073-.032-.143t-.059-.135l-1.965-3.493Q22.25 13.986 22.25 11q0-3.278-3.088-5.554Q16.182 3.25 12 3.25T4.838 5.446M12 8.75q1.604 0 2.77.5q1.48.634 1.48 1.75t-1.48 1.75q-1.166.5-2.77.5q-4.25 0-4.25-2.25T12 8.75");
}

</style>
