<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g45fpcblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:diamond-structure" /></template>
<style>
.g45fpcblb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.25q-2.5 0-2.5 2.5q0 2.092 1.75 2.433v2.371Q9 8.902 9 11.5q0 .34.039.642l-3.1 1.55Q5.315 13 4 13q-2.5 0-2.5 2.5T4 18t2.5-2.5q0-.21-.018-.403l3.093-1.546q.708.91 2.289.947l.528 3.163Q11 18.135 11 20q0 2.5 2.5 2.5T16 20q0-2.298-2.112-2.484l-.536-3.217q.675-.236 1.073-.748l3.093 1.546q-.018.193-.018.403q0 2.5 2.5 2.5t2.5-2.5T20 13q-1.315 0-1.939.692l-3.1-1.55Q15 11.84 15 11.5q0-2.598-2.25-2.946V6.142q.566-.173 1.018-.624q.732-.732.732-1.768t-.732-1.768T12 1.25");
}

</style>
