<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wkktfsbez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ai-cursor" /></template>
<style>
.wkktfsbez {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.814 4.329v.001l.139.323q.118.276.394.394l.324.139q.701.3.701 1.064t-.702 1.064l-.323.139q-.276.118-.394.394l-.139.324q-.3.701-1.064.701t-1.064-.702l-.139-.323q-.118-.276-.394-.394l-.324-.139q-.701-.3-.701-1.064t.702-1.064l.323-.139q.276-.118.394-.394l.139-.324q.3-.701 1.064-.701q.763 0 1.064.701M4.25 8.61v8.325q.001 1.222 1.122 1.71q1.12.487 2.014-.346l.52-.486q.262-.244.616-.194q.355.05.539.357l1.384 2.306q1.035 1.725 2.794.749q.74-.411.959-1.228q.218-.818-.217-1.543l-1.121-1.867q-.212-.353-.027-.722t.596-.41l.148-.015q1.184-.117 1.521-1.261q.337-1.145-.598-1.886l-6.599-5.25q-1.106-.88-2.378-.266T4.25 8.61");
}

</style>
