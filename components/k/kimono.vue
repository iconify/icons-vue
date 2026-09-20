<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="j3k8s4utt"/><path class="qufim-b6e"/><path class="d2i65xb4u"/><path class="uwacw3apr"/><path class="fns_b6b_q"/><path class="s7q9vpbtx"/><path class="kldj5nblr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:kimono" /></template>
<style>
.d2i65xb4u {
  fill: var(--svg-color--269, #269);
  d: path("M17.985 8.761L11 14h2l5.094-5.094z");
}

.fns_b6b_q {
  fill: var(--svg-color--fff, #fff);
  d: path("M25 18s-1.167 1-7 1s-7-1-7-1v-2h14zm0-18l-7 9l-7-9z");
}

.j3k8s4utt {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M22 0h3l5 2.808l5 23.307L26 27l-6-16.423M14 0h-3L6 2.808L1 26.115L10 27l6-16.423");
}

.kldj5nblr {
  fill: var(--svg-color--269, #269);
  d: path("M25 25V4l2 23zm-14 0V4L9 27z");
}

.qufim-b6e {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M11 5h14v31H11z");
}

.s7q9vpbtx {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M20.333 0L18 3l-2.333-3z");
}

.uwacw3apr {
  fill: var(--svg-color--88c9f9, #88c9f9);
  d: path("M25 20s-1.167 1-7 1s-7-1-7-1v-6h14z");
}

</style>
