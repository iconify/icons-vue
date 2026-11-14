<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2-x-txvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cheapest-route" /></template>
<style>
.n2-x-txvq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.5 5.5q0-3-3-3t-3 3q0 2.548 2.164 2.932q-.623 2.33-5.736 2.821q-3.379.325-4.715.951q-2.152 1.007-2.424 3.344Q2.5 15.879 2.5 18.5q0 3 3 3t3-3q0-2.548-2.164-2.932q.623-2.33 5.736-2.821q3.379-.325 4.715-.951q2.152-1.007 2.424-3.344Q21.5 8.121 21.5 5.5M17 14.25q-3.75 0-3.75 3.75T17 21.75h2q3.75 0 3.75-3.75T19 14.25zM14.75 18q0-2.25 2.25-2.25T19.25 18T17 20.25T14.75 18m6.5 0q0 1.371-.835 1.906q.335-.785.335-1.906t-.335-1.906q.835.535.835 1.906");
}

</style>
