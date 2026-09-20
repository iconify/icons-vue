<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1zi3cb9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:calendar-clock" /></template>
<style>
.f1zi3cb9v {
  fill: currentColor;
  d: path("M5.616 21q-.691 0-1.153-.462T4 19.385V6.615q0-.69.463-1.152T5.616 5h1.769V2.77h1.077V5h7.154V2.77h1V5h1.769q.69 0 1.153.463T20 6.616v4.751q0 .214-.143.357t-.357.143t-.357-.143t-.143-.357v-.752H5v8.77q0 .23.192.423t.423.192h6.435q.214 0 .357.143t.143.357t-.143.357t-.357.143zm9.933-.164Q14.385 19.67 14.385 18t1.164-2.835T18.384 14q1.672 0 2.836 1.165q1.165 1.164 1.165 2.835t-1.165 2.836T18.385 22t-2.836-1.164m4.492-.634l.546-.546l-1.818-1.818v-2.722H18v3.046z");
}

</style>
