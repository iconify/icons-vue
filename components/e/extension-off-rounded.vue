<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fq75skbya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:extension-off-rounded" /></template>
<style>
.fq75skbya {
  fill: currentColor;
  d: path("M19.116 16.304L7.58 4.769h1.104q.156-1.121.957-1.887q.802-.767 1.916-.767q1.108 0 1.91.767q.801.766.963 1.887h3.242q.594 0 1.018.424t.425 1.038v3.485q.842.257 1.363 1.011T21 12.442q0 .93-.521 1.674t-1.363 1.053zM5.442 20.116q-.6 0-1.02-.431Q4 19.254 4 18.654v-2.721q0-.218.133-.363t.35-.195q1.013-.22 1.678-1.018q.666-.8.666-1.915q0-1.013-.666-1.829q-.665-.815-1.678-1.098q-.218-.056-.35-.21T4 8.933V4.577l15.5 15.539zm15.45 1.484q-.165.166-.356.166q-.192 0-.357-.166L2.394 3.821q-.146-.146-.156-.347t.156-.366t.357-.166t.357.166l17.784 17.784q.147.147.156.345t-.156.363");
}

</style>
