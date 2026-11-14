<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ujcy8ybmd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:briefcase-off" /></template>
<style>
.ujcy8ybmd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.125 5.75H15.75V4.5q0-1.75-1.75-1.75h-4q-1.75 0-1.75 1.75v1.25H6.875q-.146 0-.289.007l13.813 13.814q.179-.151.35-.322q1.501-1.501 1.501-3.624v-4.75q0-2.123-1.501-3.624T17.125 5.75M9.75 4.5v1.25h4.5V4.5q0-.25-.25-.25h-4q-.25 0-.25.25m-5.72.47l16 16q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-16-16q-.053-.052-.094-.113t-.069-.13t-.043-.141Q2.75 5.574 2.75 5.5t.014-.146t.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094m-2.28 5.905q0-1.824 1.108-3.189L15.922 20.75H6.875q-2.123 0-3.624-1.501T1.75 15.625z");
}

</style>
