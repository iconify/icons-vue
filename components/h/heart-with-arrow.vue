<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="q2_k9hbsz"/><path class="a6nxoqszd"/><path class="e1qpy4bwc"/><path class="f5l5db_dk"/><path class="y2e90ib5s"/><path class="vbe0w5z-y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:heart-with-arrow" /></template>
<style>
.a6nxoqszd {
  fill: var(--svg-color--42ade2, #42ade2);
  d: path("M4.2 61s-.7-8.3 6.4-15.3l2.1 6.9z");
}

.e1qpy4bwc {
  fill: var(--svg-color--467591, #467591);
  d: path("M4.2 61s8.3.7 15.4-6.4l-6.9-2.1z");
}

.f5l5db_dk {
  fill: var(--svg-color--ff5a79, #ff5a79);
  d: path("M54.7 24.3c-5.7-15-24.2-8.3-26-.8c-2.4-8-20.4-14-26 .8c-6.1 16.4 23.8 31.2 26 33.6c2.2-1.9 32.2-17.4 26-33.6");
}

.q2_k9hbsz {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("m12.7 54.6l-2-2.1l19.1-19l2.1 2z");
}

.vbe0w5z-y {
  fill: var(--svg-color--467591, #467591);
  d: path("M40.9 21.7s-.4-9.9 8.4-18.7l2.2 8.1zm2.3 2.3s9.9.4 18.8-8.4l-8.2-2.2z");
}

.y2e90ib5s {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("m37.1 30.1l-2.4-2.3l16.8-16.7l2.3 2.4z");
}

</style>
