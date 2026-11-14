<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d44p17a6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chemical-storage" /></template>
<style>
.d44p17a6w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19.5 3.75h-15q-1.139 0-1.945.805q-.805.806-.805 1.945q0 2.031 1.5 2.562V18.5q0 2.75 2.75 2.75h12q2.75 0 2.75-2.75V9.062q1.5-.531 1.5-2.562q0-2.75-2.75-2.75M4.75 18.5V9.25h14.5v9.25q0 1.25-1.25 1.25H6q-1.25 0-1.25-1.25m6.5-5.5h1.5v-.25q0-.75-.75-.75t-.75.75zm3 .2q.418.183.768.532q.732.732.732 1.768v.5q0 1.036-.732 1.768t-1.768.732h-2.5q-2.5 0-2.5-2.5v-.5q0-1.936 1.5-2.373v-.377q0-2.25 2.25-2.25t2.25 2.25z");
}

</style>
