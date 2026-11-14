<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tvf051i3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:carpet-floor" /></template>
<style>
.tvf051i3b {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 13q0-2.175 1.538-3.712Q4.825 7.75 7 7.75t3.712 1.538Q12.25 10.825 12.25 13q0 .654-.139 1.25H21.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v2.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H7q-2.175 0-3.712-1.538Q1.75 15.175 1.75 13m3 0q0-2.25 2.25-2.25T9.25 13T7 15.25T4.75 13m5.924 3.75H20.75v-1h-9.264q-.32.509-.774.962z");
}

</style>
