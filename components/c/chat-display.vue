<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3wubcbvq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chat-display" /></template>
<style>
.m3wubcbvq {
  fill: currentColor;
  d: path("M6.5 10.5h11v-1h-11zm0-3h11v-1h-11zM9.942 17H6.077L3 20.077V4.616q0-.691.463-1.153T4.615 3h14.77q.69 0 1.152.463T21 4.616v8.203q-.239-.16-.482-.24T20 12.5H6.5v1h4.814q-.641.508-1.006 1.258q-.366.75-.366 1.627zm4 4q-.69 0-1.153-.462t-.462-1.153V16.5q0-.69.463-1.153t1.152-.462h5.443q.69 0 1.153.462T21 16.5v2.885q0 .69-.462 1.152T19.385 21zm0-1h5.443q.269 0 .442-.173t.173-.442V16.5q0-.27-.173-.442q-.173-.174-.442-.174h-5.443q-.269 0-.442.174q-.173.173-.173.442v2.885q0 .269.173.442t.442.173");
}

</style>
