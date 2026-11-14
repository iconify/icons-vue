<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfjoowbmp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:face-cushion" /></template>
<style>
.mfjoowbmp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 3.25h-11q-2.175 0-3.712 1.538Q1.25 6.325 1.25 8.5v7q0 2.175 1.538 3.712Q4.325 20.75 6.5 20.75h3q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-1.75 1.75-1.75T13.75 20q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h3q2.175 0 3.712-1.538q1.538-1.537 1.538-3.712v-7q0-2.175-1.538-3.712Q19.675 3.25 17.5 3.25M6.5 6h11Q20 6 20 8.5v7q0 2.5-2.5 2.5h-1q-.097 0-.191-.025q-.094-.024-.178-.072q-.085-.048-.154-.116q-.07-.067-.12-.151q-1.311-2.182-3.857-2.182t-3.857 2.182q-.05.084-.12.151q-.069.068-.154.116t-.178.072Q7.597 18 7.5 18h-1Q4 18 4 15.5v-7Q4 6 6.5 6");
}

</style>
