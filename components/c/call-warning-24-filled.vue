<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sq8pgqk0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:call-warning-24-filled" /></template>
<style>
.sq8pgqk0a {
  fill: currentColor;
  d: path("M6.85 2.095c1.008-.323 2.086.199 2.518 1.218l.86 2.027c.375.883.166 1.922-.514 2.568L7.82 9.706q.175 1.614 1.084 3.177a8.7 8.7 0 0 0 2.272 2.595l2.274-.76c.863-.287 1.802.044 2.331.821l1.233 1.81c.614.904.504 2.15-.26 2.917l-.817.82c-.813.817-1.976 1.114-3.051.778q-3.81-1.188-7.003-7.053q-3.2-5.876-2.26-9.968c.265-1.148 1.083-2.063 2.15-2.404zm8.311-.265c.553-1.107 2.133-1.107 2.686 0l3.997 7.998A1.5 1.5 0 0 1 20.5 12h-7.994a1.5 1.5 0 0 1-1.343-2.172zm1.343 7.168a.5.5 0 1 0 0 1a.5.5 0 0 0 0-1m0-5.003a.5.5 0 0 0-.5.5v3.002a.5.5 0 1 0 1 0V4.495a.5.5 0 0 0-.5-.5");
}

</style>
