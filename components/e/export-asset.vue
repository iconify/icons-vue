<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgflxwb6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:export-asset" /></template>
<style>
.xgflxwb6s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.591 3.031l2.217 2.217q.622.625.285 1.438t-1.217.814q-.626 0-.626.625V15q0 2.25-2.25 2.25T9.75 15V8.125q0-.625-.625-.625q-.881-.002-1.218-.814q-.337-.813.283-1.437l2.219-2.218q.659-.66 1.591-.66t1.591.66M6.75 11.5q0-1.25 1.25-1.25q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T8 8.75q-2.75 0-2.75 2.75v8q0 2.75 2.75 2.75h8q2.75 0 2.75-2.75v-8q0-2.75-2.75-2.75q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014q1.25 0 1.25 1.25v8q0 1.25-1.25 1.25H8q-1.25 0-1.25-1.25z");
}

</style>
