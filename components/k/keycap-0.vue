<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="vxonir6if"/><path class="l-31-qbep"/><path class="m8de_ixuf"/><path class="bi80bugoc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:keycap-0" /></template>
<style>
.bi80bugoc {
  fill: var(--svg-color--fff, #fff);
  d: path("M62.79 25C42.87 25 30 40.47 30 64.42s12.87 39.43 32.79 39.43s32.79-15.47 32.79-39.43C95.59 40.47 82.71 25 62.79 25m0 60.21c-9.53 0-12.91-11.2-12.91-20.79c0-9.58 3.38-20.78 12.91-20.78s12.92 11.2 12.92 20.78c0 9.59-3.39 20.79-12.92 20.79");
}

.l-31-qbep {
  fill: var(--svg-color--f79329, #f79329);
  d: path("M124.48 3.52L3.52 124.48C5.7 126.65 8.7 128 12 128h104c6.6 0 12-5.4 12-12V12c0-3.3-1.35-6.3-3.52-8.48");
}

.m8de_ixuf {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M112 101c0 6.63-5.37 12-12 12H27.89c-6.6 0-12-5.4-12-12V28.9c0-6.6 5.4-12 12-12H100c6.63 0 12 5.37 12 12z");
}

.vxonir6if {
  fill: var(--svg-color--fcc21b, #fcc21b);
  d: path("M116 128H12c-6.6 0-12-5.4-12-12V12C0 5.4 5.4 0 12 0h104c6.6 0 12 5.4 12 12v104c0 6.6-5.4 12-12 12");
}

</style>
