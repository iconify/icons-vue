<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h7sc6nbrs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:audio-video-receiver-outline" /></template>
<style>
.h7sc6nbrs {
  fill: currentColor;
  d: path("M4.616 14.692h14.769q.269 0 .442-.173t.173-.442V7.731q0-.27-.173-.442q-.173-.173-.442-.173H4.615q-.269 0-.442.173T4 7.73v6.346q0 .27.173.442q.173.173.443.173m.884 2.27q-.213 0-.357-.144T5 16.461v-.769h-.385q-.69 0-1.153-.462T3 14.077V7.731q0-.69.463-1.153t1.152-.462h14.77q.69 0 1.152.462T21 7.731v6.346q0 .69-.463 1.153t-1.153.462H19v.77q0 .213-.143.356t-.357.143t-.357-.143t-.143-.356v-.77H6v.77q0 .213-.143.356t-.357.143M4 14.693V7.116zm13.682-2.626q.434-.433.434-1.066t-.434-1.066t-1.066-.434t-1.067.434q-.433.433-.433 1.066t.433 1.066t1.067.434t1.066-.434M6.385 12.5h6.461v-3H6.385z");
}

</style>
