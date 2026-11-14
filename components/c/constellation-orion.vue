<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qpi8xcbqm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:constellation-orion" /></template>
<style>
.qpi8xcbqm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 3.5q0-2 2-2t2 2t-2 2t-2-2M18 2q-2 0-2 2t2 2t2-2t-2-2M7.491 6.523q-.631.227-1.488.227l1.066 4.48Q7.67 11 8.5 11h.057zm9.977.703l-.093.225q-.575-.364-1.444-.434l.092-.222q.587.351 1.445.431M13.75 10q0-1.75 1.75-1.75T17.25 10t-1.75 1.75T13.75 10m-1.75.25q-1.75 0-1.75 1.75T12 13.75T13.75 12T12 10.25M6.75 14q0-1.75 1.75-1.75T10.25 14T8.5 15.75T6.75 14m10.444 3.111l-1.441-4.117q.871-.039 1.466-.354l1.441 4.119q-.86.049-1.466.352m-11.332.205l.513-.951q.532.454 1.389.583l-.511.949q-.546-.44-1.391-.581M21 20q0-2-2-2t-2 2t2 2t2-2m-18 .5q0-2 2-2t2 2t-2 2t-2-2");
}

</style>
