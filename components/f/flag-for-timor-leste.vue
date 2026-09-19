<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="uo_rpwscp"/><path class="z24meyjdw"/><path class="yxv-qq44z"/><path class="w9blz8c0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-timor-leste" /></template>
<style>
.uo_rpwscp {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M32 2c-7.6 0-14.6 2.9-19.9 7.6v44.9C17.4 59.1 24.4 62 32 62c16.6 0 30-13.4 30-30S48.6 2 32 2");
}

.w9blz8c0x {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.3 33.9l2.4 5.1l1-5.3l5.3-.4l-4.8-3l1-5.3l-3.9 3.5l-4.8-2.9l2.4 5.1L5 34.3z");
}

.yxv-qq44z {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M8.4 13.4C4.4 18.5 2 25 2 32s2.4 13.5 6.4 18.6L27 32z");
}

.z24meyjdw {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M12.1 9.6q-1.95 1.8-3.6 3.9v37.1q1.65 2.1 3.6 3.9L42 32z");
}

</style>
