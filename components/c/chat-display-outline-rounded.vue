<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wguk59zlc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chat-display-outline-rounded" /></template>
<style>
.wguk59zlc {
  fill: currentColor;
  d: path("M7 10.5h10q.214 0 .357-.143T17.5 10t-.143-.357T17 9.5H7q-.213 0-.357.143T6.5 10t.143.357T7 10.5m0-3h10q.214 0 .357-.143T17.5 7t-.143-.357T17 6.5H7q-.213 0-.357.143T6.5 7t.143.357T7 7.5M6.077 17l-1.704 1.704q-.379.379-.876.174T3 18.133V4.616q0-.691.463-1.153T4.615 3h14.77q.69 0 1.152.463T21 4.616v7.423q0 .213-.143.356t-.357.144t-.357-.144T20 12.04V4.616q0-.231-.192-.424T19.385 4H4.615q-.23 0-.423.192T4 4.615v13.03L5.65 16h3.812q.213 0 .356.143t.144.357t-.144.357t-.356.143zM7 13.5h3.814q.213 0 .356-.143t.143-.357t-.143-.357t-.357-.143H7q-.213 0-.357.143T6.5 13t.143.357T7 13.5m6.942 7.5q-.69 0-1.152-.462t-.463-1.153V16.5q0-.69.463-1.153t1.152-.462h5.443q.69 0 1.153.462T21 16.5v2.885q0 .69-.462 1.152T19.385 21zm0-1h5.443q.269 0 .442-.173t.173-.442V16.5q0-.27-.173-.442q-.173-.174-.442-.174h-5.443q-.269 0-.442.174q-.173.173-.173.442v2.885q0 .269.173.442t.442.173M4 12.5v5.144V4z");
}

</style>
