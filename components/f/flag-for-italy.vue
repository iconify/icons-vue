<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="tjq_j4_wv"/><path class="msj91kavx"/><path class="ys9xjfbrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-italy" /></template>
<style>
.msj91kavx {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M61.7 32c0-13.1-8.4-24.2-20-28.3v56.6c11.7-4.1 20-15.2 20-28.3");
}

.tjq_j4_wv {
  fill: var(--svg-color--75a843, #75a843);
  d: path("M1.7 32c0 13.1 8.4 24.2 20 28.3V3.7C10.1 7.8 1.7 18.9 1.7 32");
}

.ys9xjfbrf {
  fill: var(--svg-color--fff, #fff);
  d: path("M21.7 60.3c3.1 1.1 6.5 1.7 10 1.7s6.9-.6 10-1.7V3.7C38.6 2.6 35.2 2 31.7 2s-6.9.6-10 1.7z");
}

</style>
