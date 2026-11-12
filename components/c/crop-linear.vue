<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xoi8enb4l"/><path class="dux539s4k"/><path class="pjfppgavf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:crop-linear" /></template>
<style>
.dux539s4k {
  d: path("M8 5H11C14.7712 5 16.6569 5 17.8284 6.17157C19 7.34315 19 9.22876 19 13V16M2 5H5M19 19V22");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pjfppgavf {
  d: path("M11.5 15.5H12.5C13.9142 15.5 14.6213 15.5 15.0607 15.0607C15.5 14.6213 15.5 13.9142 15.5 12.5V11.5C15.5 10.0858 15.5 9.37868 15.0607 8.93934C14.6213 8.5 13.9142 8.5 12.5 8.5H11.5C10.0858 8.5 9.37868 8.5 8.93934 8.93934C8.5 9.37868 8.5 10.0858 8.5 11.5V12.5C8.5 13.9142 8.5 14.6213 8.93934 15.0607C9.37868 15.5 10.0858 15.5 11.5 15.5Z");
}

.xoi8enb4l {
  d: path("M22 19H13C9.22876 19 7.34315 19 6.17157 17.8284C5 16.6569 5 14.7712 5 11V2");
}

</style>
