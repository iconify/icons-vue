<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qzi57gg-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cloth-napkin" /></template>
<style>
.qzi57gg-i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.5 2.75H14q-.149 0-.287.057t-.243.163L2.97 13.469v.001q-.106.105-.163.243T2.75 14v4.5q0 2.75 2.75 2.75h13q2.75 0 2.75-2.75v-13q0-2.75-2.75-2.75m-14.25 12H14q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146V4.25h3.75q1.25 0 1.25 1.25v13q0 1.25-1.25 1.25h-13q-1.25 0-1.25-1.25zm9-9.439v7.939H5.311z");
}

</style>
