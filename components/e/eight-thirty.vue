<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="qc_jeebdo"/><path class="jr522jbyg"/><path class="nt8a-c-9g"/><path class="kw18wgebq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:eight-thirty" /></template>
<style>
.jr522jbyg {
  fill: var(--svg-color--98a9b4, #98a9b4);
  d: path("M0 32.05C0 49.723 14.378 64.1 32.05 64.1c17.673 0 32.05-14.379 32.05-32.05C64.1 14.373 49.722 0 32.05 0S0 14.378 0 32.05m6.24 0c0-14.236 11.581-25.816 25.813-25.816c14.234 0 25.814 11.58 25.814 25.816c0 14.232-11.58 25.812-25.814 25.812c-14.232 0-25.813-11.58-25.813-25.812");
}

.kw18wgebq {
  fill: var(--svg-color--788288, #788288);
  d: path("M17.77 38.925c-1.166.845-1.613 2.216-1 3.062c.614.845 2.06.847 3.224 0l12.376-8.965c1.163-.845 1.613-2.222.998-3.063c-.612-.847-2.056-.849-3.22-.008z");
}

.nt8a-c-9g {
  fill: var(--svg-color--85939c, #85939c);
  d: path("M30.17 53.05c0 1.439.849 2.605 1.894 2.605c1.042 0 1.895-1.166 1.895-2.605V31.93c0-1.441-.853-2.61-1.895-2.61c-1.045 0-1.894 1.168-1.894 2.61z");
}

.qc_jeebdo {
  cx: 32.05px;
  cy: 32.05px;
  r: 29.694px;
  fill: var(--svg-color--e0e7ec, #e0e7ec);
}

</style>
