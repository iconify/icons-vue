<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghioz5b0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:design-system-book" /></template>
<style>
.ghioz5b0g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 4.5v15q0 2.75 2.75 2.75h12q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-19q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T19 1.75H7q-2.75 0-2.75 2.75M7 16.75q-.719 0-1.25.188V4.5q0-1.25 1.25-1.25h11.25v13.5zm6.227-9.431l.292.738q.12.304.423.423l.739.293q.834.33.834 1.227t-.834 1.227l-.738.292q-.304.12-.423.423l-.293.739q-.33.834-1.227.834t-1.227-.834l-.292-.738q-.12-.304-.423-.423l-.739-.293q-.834-.33-.834-1.227t.834-1.227l.738-.292q.304-.12.423-.423l.293-.739q.33-.834 1.227-.834t1.227.834M18.25 20.75H7q-1.25 0-1.25-1.25T7 18.25h11.25z");
}

</style>
