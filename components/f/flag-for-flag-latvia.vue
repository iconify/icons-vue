<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fss0ty4sj"/><path class="j7py13bsv"/><path class="v246_pbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-latvia" /></template>
<style>
.fss0ty4sj {
  fill: var(--svg-color--c94747, #c94747);
  d: path("M61.2 39V25C58 11.8 46.2 2 32 2S6 11.8 2.8 25v14C6 52.2 17.8 62 32 62s26-9.8 29.2-23");
}

.j7py13bsv {
  fill: var(--svg-color--c28fef, #c28fef);
  d: path("M61.2 39V25C58 11.8 46.2 2 32 2S6 11.8 2.8 25v14C6 52.2 17.8 62 32 62s26-9.8 29.2-23");
  opacity: var(--svg-opacity--0-15, 0.15);
}

.v246_pbon {
  fill: var(--svg-color--fff, #fff);
  d: path("M2 32c0 2.4.3 4.8.8 7h58.3c.5-2.2.8-4.6.8-7s-.3-4.8-.8-7H2.8c-.5 2.2-.8 4.6-.8 7");
}

</style>
