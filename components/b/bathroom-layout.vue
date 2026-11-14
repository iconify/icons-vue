<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j-a25xbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bathroom-layout" /></template>
<style>
.j-a25xbhj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 2.25H6q-1.76 0-3.005 1.245T1.75 6.5v11q0 1.76 1.245 3.005T6 21.75h12q1.76 0 3.005-1.245T22.25 17.5v-11q0-1.76-1.245-3.005T18 2.25m-10.25 3q1.243 0 2.121.879q.879.878.879 2.121v7.5q0 3-3 3t-3-3v-7.5q0-1.243.879-2.121q.878-.879 2.121-.879m9.25 0q2.25 0 2.25 2.25q0 1.372-.837 1.908q.587.994.587 2.842q0 4-2.75 4t-2.75-4q0-1.848.587-2.842q-.837-.536-.837-1.908q0-2.25 2.25-2.25z");
}

</style>
