<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="ft5dv1b6b"><path class="jmpc1xihx"/><path class="wa_l6bcqs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-england" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jmpc1xihx {
  fill: var(--svg-color--fff, #fff);
  d: path("M38 2.6H26C14.3 5 5 14.2 2.6 26v12C5 49.8 14.3 59 26 61.4h12C49.8 59 59 49.7 61.4 38V26C59 14.2 49.7 5 38 2.6");
}

.wa_l6bcqs {
  fill: var(--svg-color--ce1124, #CE1124);
  d: path("M61.179 39A30 30 0 0 0 62 32c0-2.41-.284-4.754-.821-7H39V2.821A30 30 0 0 0 32 2c-2.41 0-4.754.284-7 .821V25H2.821A30 30 0 0 0 2 32c0 2.41.284 4.754.821 7H25v22.179A30 30 0 0 0 32 62c2.41 0 4.754-.284 7-.821V39z");
}

</style>
