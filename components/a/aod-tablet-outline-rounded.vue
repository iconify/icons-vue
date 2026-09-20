<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yue7_6bft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:aod-tablet-outline-rounded" /></template>
<style>
.yue7_6bft {
  fill: currentColor;
  d: path("M8.942 11.192q-.19 0-.316-.126T8.5 10.75t.126-.316t.316-.126h6.116q.19 0 .316.126t.126.316t-.126.316t-.316.126zm1 3q-.19 0-.316-.126T9.5 13.75t.126-.316t.316-.126h4.116q.19 0 .316.126t.126.316t-.126.316t-.316.126zM3.616 19q-.672 0-1.144-.472T2 17.385V6.615q0-.67.472-1.143Q2.944 5 3.616 5h16.769q.67 0 1.143.472q.472.472.472 1.144v10.769q0 .67-.472 1.143q-.472.472-1.143.472zM4.5 6h-.885q-.269 0-.442.173T3 6.616v10.769q0 .269.173.442t.443.173H4.5zm1 12h13V6h-13zm14-12v12h.885q.269 0 .442-.173t.173-.442V6.615q0-.269-.173-.442T20.385 6zm0 0H21zm-15 0H3z");
}

</style>
