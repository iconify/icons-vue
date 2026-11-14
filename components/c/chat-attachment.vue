<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cc-txjb2f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chat-attachment" /></template>
<style>
.cc-txjb2f {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M19 2H5q-1.139 0-1.945.805q-.805.806-.805 1.945V15.5q0 2.75 2.75 2.75h1.25V21q0 .136.048.264q.048.127.138.23q.098.112.232.178q.133.066.282.076t.29-.038q.142-.047.254-.146l3.788-3.314H19q2.75 0 2.75-2.75V4.75Q21.75 2 19 2m-6.25 11q0 .75.75.75t.75-.75V8.5q0-2.25-2.25-2.25T9.75 8.5v6q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T9 15.25t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-6q0-3.75 3.75-3.75t3.75 3.75V13q0 2.25-2.25 2.25T11.25 13V9q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 8.25t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146z");
}

</style>
