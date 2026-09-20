<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps6dc_uzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fullscreen-exit-outline-rounded" /></template>
<style>
.ps6dc_uzn {
  fill: currentColor;
  d: path("M7.423 16.577H4.5q-.213 0-.356-.144T4 16.076t.144-.356t.356-.143h3.116q.343 0 .575.232t.232.575V19.5q0 .213-.144.356q-.144.144-.357.144t-.356-.144t-.143-.356zm9.173 0V19.5q0 .213-.144.356t-.357.144t-.355-.144t-.144-.356v-3.116q0-.343.232-.575q.233-.232.576-.232h3.115q.213 0 .357.144q.143.144.143.356q0 .213-.143.357t-.357.143zM7.423 7.423V4.5q0-.213.144-.356T7.924 4t.356.144t.143.356v3.116q0 .343-.232.575t-.575.232H4.5q-.213 0-.356-.144Q4 8.135 4 7.922t.144-.356t.356-.143zm9.173 0h2.923q.213 0 .357.144t.143.357t-.143.356t-.357.143h-3.115q-.344 0-.576-.232t-.232-.576V4.5q0-.213.144-.356q.144-.144.357-.144t.356.144t.143.356z");
}

</style>
