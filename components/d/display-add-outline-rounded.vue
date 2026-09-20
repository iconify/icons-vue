<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqs_pd51l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:display-add-outline-rounded" /></template>
<style>
.kqs_pd51l {
  fill: currentColor;
  d: path("M4 5v12zm5 13H4.616q-.691 0-1.153-.462T3 16.384V5.616q0-.691.463-1.153T4.615 4h7.618q.212 0 .356.144t.144.357t-.144.356t-.356.143H4.615q-.23 0-.423.192T4 5.616v10.769q0 .23.192.423t.423.192h14.77q.23 0 .423-.192t.192-.423v-4.893q0-.212.144-.356t.357-.144t.356.144t.143.356v4.893q0 .69-.462 1.153T19.385 18H15v1.192q0 .344-.232.576t-.576.232H9.808q-.343 0-.576-.232T9 19.192zm9-12h-2.5q-.213 0-.356-.144T15 5.499t.144-.356T15.5 5H18V2.5q0-.213.144-.356T18.501 2t.356.144T19 2.5V5h2.5q.213 0 .356.144t.144.357t-.144.356T21.5 6H19v2.5q0 .213-.144.356T18.499 9t-.356-.144T18 8.5z");
}

</style>
