<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbfngdcyj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:icecream-rounded" /></template>
<style>
.fbfngdcyj {
  fill: currentColor;
  d: path("M4 10q0-.967.603-1.81q.603-.842 1.882-1.21q.315-2.332 1.92-3.656T12 2t3.595 1.324t1.92 3.657q1.28.367 1.882 1.21Q20 9.033 20 10q0 1.587-1.22 2.427t-2.618.38l-3.39 6.647q-.126.217-.315.323t-.407.106t-.41-.106t-.317-.323l-3.396-6.646q-1.39.517-2.659-.362T4 10m8.05 8.65l3.2-6.25l-.27-.23q-.772.395-1.54.613Q12.674 13 12 13q-.598 0-1.353-.188q-.755-.189-1.54-.643l-.268.231z");
}

</style>
