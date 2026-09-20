<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ns0vi1bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:door-sensor-rounded" /></template>
<style>
.ns0vi1bdk {
  fill: currentColor;
  d: path("M9.616 20q-.667 0-1.141-.475T8 18.386V16.27h4.27q.523 0 .896-.371q.372-.372.372-.893t-.372-.898t-.897-.376H8V5.616q0-.667.475-1.141T9.615 4h4.77q.666 0 1.14.475T16 5.615v12.77q0 .666-.475 1.14t-1.14.475zm-3.731-4.5q-.213 0-.357-.144t-.143-.357t.143-.356t.357-.143h6.384q.213 0 .356.144t.144.357t-.144.356t-.356.143zm6.655-5.96q.23-.23.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23t.54-.23m6.603-1.184Q19 8.213 19 8V4q0-.213.144-.356t.357-.144t.356.144T20 4v4q0 .213-.144.356t-.357.144t-.356-.144");
}

</style>
