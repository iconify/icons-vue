<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wrg5fvfue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:lane-arrow-merge-right" /></template>
<style>
.wrg5fvfue {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 16.5v4q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-4q0-1.536 3.585-3.329Q15.25 10.964 15.25 8.5V5.311l2.22 2.219q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.106-.105.163-.243T18.75 7t-.057-.287t-.163-.243l-3.499-3.5h-.001q-.105-.106-.243-.163T14.5 2.75q-.147 0-.283.055t-.24.158l-.007.007h-.001l-3.499 3.5q-.053.052-.094.113t-.069.13t-.043.141T10.25 7t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163T11 7.75t.287-.057t.243-.163l2.22-2.219V8.5q0 1.536-3.585 3.329Q5.75 14.036 5.75 16.5");
}

</style>
