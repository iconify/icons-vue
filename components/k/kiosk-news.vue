<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q253gvbqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:kiosk-news" /></template>
<style>
.q253gvbqk {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m2.914 5.994l1-2Q4.536 2.75 5.927 2.75h12.146q1.391 0 2.013 1.243l1 2.001q.561 1.122-.099 2.189q-.305.494-.737.759V21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-15q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V8.942q-.432-.265-.737-.759q-.66-1.067-.099-2.189M18.75 9.25H5.25v5.5h2.621Q7.75 14.4 7.75 14v-1.25q0-2.25 2.25-2.25h4q.932 0 1.591.659t.659 1.591V14q0 .4-.121.75h2.621zm-6.75 7H5.25v4.5h13.5v-4.5z");
}

</style>
