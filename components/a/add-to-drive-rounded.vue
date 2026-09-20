<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m264z81dy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:add-to-drive-rounded" /></template>
<style>
.m264z81dy {
  fill: currentColor;
  d: path("M7.044 20q-1.04 0-1.933-.504q-.892-.504-1.415-1.383q-.523-.88-.523-1.885t.523-1.882l1.09-1.846h3.906l4.37 7.5zm-1.678-8.5l3.311-5.596q.523-.877 1.414-1.39Q10.981 4 12 4q1.027 0 1.904.514q.877.513 1.4 1.39l1.365 2.302l-1.934 3.294zM18 19h-2.5q-.213 0-.356-.144T15 18.499t.144-.356T15.5 18H18v-2.5q0-.213.144-.356t.357-.144t.356.144t.143.356V18h2.5q.213 0 .356.144t.144.357t-.144.356T21.5 19H19v2.5q0 .213-.144.356t-.357.144t-.356-.144T18 21.5zm-3.652-4.837l2.9-4.982l2 3.377q-1.344-.175-2.624.24q-1.28.416-2.276 1.366");
}

</style>
