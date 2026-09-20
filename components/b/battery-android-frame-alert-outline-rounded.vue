<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xktf7d2qr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-frame-alert-outline-rounded" /></template>
<style>
.xktf7d2qr {
  fill: currentColor;
  d: path("M4.385 17q-.994 0-1.69-.695T2 14.615v-5.23q0-.994.696-1.69T4.385 7h13.23q.213 0 .357.144t.143.357t-.143.356t-.357.143H4.386q-.589 0-.987.398T3 9.385v5.23q0 .589.398.987t.986.398h13.27q.212 0 .356.144t.144.357t-.144.356t-.356.143zm0-3.192v-3.616q0-.343.232-.575t.575-.232h12.116q.343 0 .575.232t.233.575v3.616q0 .343-.233.575t-.575.233H5.192q-.343 0-.575-.233t-.232-.575M20.48 16.02q-.21-.21-.21-.52t.21-.521q.209-.21.52-.21t.52.21q.21.209.21.52t-.21.52q-.209.21-.52.21t-.52-.21m.163-3.048q-.143-.144-.143-.357V8q0-.213.144-.356t.357-.144t.356.144T21.5 8v4.616q0 .212-.144.356t-.357.144t-.356-.144");
}

</style>
