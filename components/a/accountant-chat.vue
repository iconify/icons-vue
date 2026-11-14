<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iivj7lbvu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:accountant-chat" /></template>
<style>
.iivj7lbvu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15 1.75h4.5q2.75 0 2.75 2.75v4q0 2.75-2.75 2.75h-2.189l-2.281 2.28q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163t-.163-.243T13.75 13v-1.938q-1.5-.531-1.5-2.562v-4q0-2.75 2.75-2.75M2.75 11q0-1.76 1.245-3.005T7 6.75t3.005 1.245T11.25 11t-1.245 3.005T7 15.25t-3.005-1.245T2.75 11M7 16.75q-5.25 0-5.25 4.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-3.25 3.75-3.25t3.75 3.25q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-4.75-5.25-4.75");
}

</style>
