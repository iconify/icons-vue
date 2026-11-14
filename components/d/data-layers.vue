<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m7objubac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:data-layers" /></template>
<style>
.m7objubac {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9 2.75h6q2.75 0 2.75 2.75T15 8.25H9q-2.75 0-2.75-2.75T9 2.75m8 6.5H7q-2.75 0-2.75 2.75T7 14.75h10q2.75 0 2.75-2.75T17 9.25m-12 6.5h14q2.75 0 2.75 2.75T19 21.25H5q-2.75 0-2.75-2.75q0-1.139.805-1.945q.806-.805 1.945-.805");
}

</style>
