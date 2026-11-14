<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tzqy8juij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:deal-stage" /></template>
<style>
.tzqy8juij {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.25 12q0-3.25 3.25-3.25q2.85 0 3.201 2.5h1.098Q9.15 8.75 12 8.75t3.201 2.5h1.098q.351-2.5 3.201-2.5q3.25 0 3.25 3.25t-3.25 3.25q-2.85 0-3.201-2.5h-1.098q-.351 2.5-3.201 2.5t-3.201-2.5H7.701q-.351 2.5-3.201 2.5q-1.346 0-2.298-.952T1.25 12");
}

</style>
