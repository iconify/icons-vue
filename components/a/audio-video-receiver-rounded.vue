<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dhoowsbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:audio-video-receiver-rounded" /></template>
<style>
.dhoowsbds {
  fill: currentColor;
  d: path("M5.5 16.962q-.213 0-.357-.144T5 16.461v-.769h-.385q-.69 0-1.153-.462T3 14.077V7.731q0-.69.463-1.153t1.152-.462h14.77q.69 0 1.152.462T21 7.731v6.346q0 .69-.463 1.153t-1.153.462H19v.77q0 .213-.143.356t-.357.143t-.357-.143t-.143-.356v-.77H6v.77q0 .213-.143.356t-.357.143m12.182-4.895q.434-.433.434-1.066t-.434-1.066t-1.066-.434t-1.067.434q-.433.433-.433 1.066t.433 1.066t1.067.434t1.066-.434m-10.49.434h4.847q.348 0 .577-.23q.23-.23.23-.578v-1.384q0-.348-.23-.578t-.577-.23H7.192q-.348 0-.577.23q-.23.23-.23.578v1.384q0 .348.23.578t.577.23");
}

</style>
