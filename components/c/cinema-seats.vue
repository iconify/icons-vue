<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x896rgvso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cinema-seats" /></template>
<style>
.x896rgvso {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.75 8v5.5q-1 .5-1 2q0 2.121 2 2.243V20.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2.75h13.5v2.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2.757q2-.122 2-2.243q0-1.5-1-2V8q0-2.75-2.75-2.75H17q-1.314 0-2 .628q-.686-.628-2-.628h-2q-1.314 0-2 .628q-.686-.628-2-.628H5.5q-1.139 0-1.945.805Q2.75 6.861 2.75 8m5.5 5.25h-4V8q0-1.25 1.25-1.25H7q1.25 0 1.25 1.25zm1.5 0V8q0-1.25 1.25-1.25h2q1.25 0 1.25 1.25v5.25zm10 0h-4V8q0-1.25 1.25-1.25h1.5q1.25 0 1.25 1.25z");
}

</style>
