<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xtp1ktmpw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:blackout-blind" /></template>
<style>
.xtp1ktmpw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 1.75H4Q1.75 1.75 1.75 4q0 2.121 2 2.243V19.5q0 2.25 2.25 2.25h12q2.25 0 2.25-2.25V6.243q2-.122 2-2.243q0-2.25-2.25-2.25m-3.5 12.5H5.25v-8h13.5v8zm-.75 1.5v2.5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-2.5h1.5v3.75q0 .75-.75.75H6q-.75 0-.75-.75v-3.75z");
}

</style>
