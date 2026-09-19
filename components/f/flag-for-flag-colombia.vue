<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="mxamjib1o"/><path class="vtd0aubir"/><path class="wpsikub0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-colombia" /></template>
<style>
.mxamjib1o {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M62 32H2c0 5.5 1.5 10.6 4 15h52c2.6-4.4 4-9.5 4-15");
}

.vtd0aubir {
  fill: var(--svg-color--ffe62e, #ffe62e);
  d: path("M32 2C15.5 2 2 15.4 2 32h60C62 15.4 48.6 2 32 2");
}

.wpsikub0m {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M32 62c11.1 0 20.8-6 26-15H6c5.3 9 14.9 15 26 15");
}

</style>
