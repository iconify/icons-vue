<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yoa0k4bjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-flashlight-on" /></template>
<style>
.yoa0k4bjz {
  fill: currentColor;
  d: path("M6 2h12v3H6zm0 5v1l2 3v11h8V11l2-3V7zm6 8.5c-.83 0-1.5-.67-1.5-1.5s.67-1.5 1.5-1.5s1.5.67 1.5 1.5s-.67 1.5-1.5 1.5");
}

</style>
