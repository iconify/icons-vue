<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsvd05yxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:atm-cassette" /></template>
<style>
.jsvd05yxb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 3.25h1.76q.12-1.5 1.74-1.5h7q1.75 0 1.75 1.75v8.125q1.5.75 1.5 3v4.25q0 3.375-3.375 3.375H5.125q-3.375 0-3.375-3.375v-4.25q0-2.25 1.5-3V6.5q0-1.75 1.75-1.75h1.76q.12-1.5 1.74-1.5m3.25 8h7.125q.193 0 .375.011V3.5q0-.25-.25-.25h-7q-.25 0-.25.25zm-1.5 0v-6.5H8.5q-.25 0-.25.25v6.25zM15.5 5q-2.75 0-2.75 2t2.75 2t2.75-2t-2.75-2M6.75 6.25H5q-.25 0-.25.25v4.761q.182-.011.375-.011H6.75zm9 10.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T15 16H9q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T9 17.5h6q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146");
}

</style>
