<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esik_gbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:badge-rounded" /></template>
<style>
.esik_gbzj {
  fill: currentColor;
  d: path("M6.308 17.423h5.384v-.142q0-.348-.189-.644q-.19-.295-.518-.437q-.443-.206-.945-.309q-.503-.103-1.04-.103t-1.04.103q-.502.103-.944.309q-.33.142-.519.437q-.19.296-.19.644zm8.134-1.538h3.116q.19 0 .316-.126t.126-.317t-.126-.316t-.316-.126h-3.116q-.19 0-.316.126t-.126.316t.126.317t.316.126m-4.6-1.236q.35-.351.35-.841t-.35-.842q-.352-.35-.842-.35t-.841.35t-.351.842q0 .49.35.841Q8.51 15 9 15t.841-.351m4.601-1.149h3.116q.19 0 .316-.126t.126-.316t-.126-.317q-.126-.125-.316-.125h-3.116q-.19 0-.316.125q-.126.126-.126.317q0 .19.126.316t.316.126M4.616 21q-.691 0-1.153-.462T3 19.385v-9.77q0-.69.463-1.152T4.615 8H10V4q0-.421.29-.71Q10.579 3 11 3h2q.421 0 .71.29q.29.289.29.71v4h5.385q.69 0 1.152.463T21 9.616v9.769q0 .69-.463 1.153T19.385 21zM11 9.77h2V4h-2z");
}

</style>
