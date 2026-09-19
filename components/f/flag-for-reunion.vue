<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="jkgb_gose"/><path class="a0j-drrlu"/><path class="xin3r_bes"/><path class="g-4zn6s7l"/><path class="o8vehgbwz"/><path class="wwy2mkbcg"/><path class="yhnqqobay"/><circle class="c31omtb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-reunion" /></template>
<style>
.a0j-drrlu {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M56 14C50.5 6.7 41.8 2 32 2c-6.8 0-13 2.2-18 6l24 24z");
}

.c31omtb4h {
  cx: 38px;
  cy: 32px;
  r: 12px;
  fill: var(--svg-color--fff, #fff);
}

.g-4zn6s7l {
  fill: var(--svg-color--699635, #699635);
  d: path("M38 32L14 56c5 3.8 11.2 6 18 6c9.8 0 18.5-4.7 24-12z");
}

.jkgb_gose {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M14 8v48l24-24z");
}

.o8vehgbwz {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M6 17c-2.5 4.4-4 9.5-4 15s1.5 10.6 4 15z");
}

.wwy2mkbcg {
  fill: var(--svg-color--fff, #fff);
  d: path("M6 17v30c1.1 2 2.5 3.8 4 5.4V11.6c-1.5 1.7-2.9 3.5-4 5.4");
}

.xin3r_bes {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M56 50c3.8-5 6-11.2 6-18s-2.2-13-6-18L38 32z");
}

.yhnqqobay {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M10 11.6v40.8c1.2 1.3 2.6 2.5 4 3.6V8c-1.4 1.1-2.8 2.3-4 3.6");
}

</style>
