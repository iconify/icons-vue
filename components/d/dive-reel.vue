<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf2sf4qmj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dive-reel" /></template>
<style>
.yf2sf4qmj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 3.75H9.999q-3.417 0-5.833 2.416T1.75 12t2.416 5.834T10 20.25t5.834-2.416T18.25 12t-2.416-5.834q-.513-.512-1.07-.916H17.5q2.25 0 2.25 2.25V20q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V7.5q0-3.75-3.75-3.75M6.75 12q0-3.25 3.25-3.25T13.25 12T10 15.25T6.75 12");
}

</style>
