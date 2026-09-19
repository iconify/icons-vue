<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="ng_s0p59z"/><path class="v3ns7ccmm"/><path class="uuo2h7bxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-benin" /></template>
<style>
.ng_s0p59z {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M22 60.3V3.7C10.4 7.8 2 18.9 2 32s8.4 24.2 20 28.3");
}

.uuo2h7bxc {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M22 32v28.3c3.1 1.1 6.5 1.7 10 1.7c16.6 0 30-13.4 30-30z");
}

.v3ns7ccmm {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M22 32h40C62 15.4 48.6 2 32 2c-3.5 0-6.9.6-10 1.7z");
}

</style>
