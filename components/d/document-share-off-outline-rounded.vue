<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ka9j5u-gl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:document-share-off-outline-rounded" /></template>
<style>
.ka9j5u-gl {
  fill: currentColor;
  d: path("M14.979 3.479L18.52 7.02q.217.218.348.518t.131.632v1.893q0 .212-.144.356t-.357.144t-.356-.144t-.143-.356V8h-4V4H7.248l-.923-.948q.063-.029.134-.04Q6.529 3 6.616 3h7.213q.331 0 .632.13t.518.349m3.455 11.574Q18 14.619 18 13.987t.434-1.067t1.066-.433t1.066.433t.434 1.067t-.434 1.066q-.433.434-1.066.434t-1.066-.434M6.616 21q-.691 0-1.153-.462T5 19.385V6.53l-2.6-2.6q-.14-.14-.15-.344t.15-.364t.354-.16t.354.16l17.4 17.4q.14.14.15.344t-.15.364t-.354.16t-.354-.16l-3.715-3.715q-.44.325-.985.288t-.948-.44t-.44-.948t.288-.985l-8-8v11.854q0 .23.192.423t.423.192h4.827q.213 0 .357.144t.143.357t-.143.356t-.357.143z");
}

</style>
