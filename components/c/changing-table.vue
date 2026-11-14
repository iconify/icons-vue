<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tghvv6b0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:changing-table" /></template>
<style>
.tghvv6b0r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 3.25q-3.25 0-3.25 3.25q0 1.158.413 1.904q-.413.165-.754.505q-.659.659-.659 1.591q0 2.121 2 2.243V20.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-7.75h12.5v7.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-7.757q2-.122 2-2.243q0-1.674-1.245-2.103q.245-.576.245-1.397q0-2.75-2.75-2.75h-4.25Q11 4.25 11 7q0 .719.188 1.25H9.416q.334-.708.334-1.75q0-3.25-3.25-3.25");
}

</style>
