<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="whl4uslhs"/><path class="v6n-zabnp"/><path class="b64yj4bnq"/><path class="p6bjdwatz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-cameroon" /></template>
<style>
.b64yj4bnq {
  fill: var(--svg-color--c94747, #c94747);
  d: path("M42 3.7C38.9 2.6 35.5 2 32 2s-6.9.6-10 1.7v56.6c3.1 1.1 6.5 1.7 10 1.7s6.9-.6 10-1.7z");
}

.p6bjdwatz {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("m32 36.2l5.3 3.8l-2-6.1l5.2-3.8H34L32 24l-2 6.1h-6.5l5.2 3.8l-2 6.1z");
}

.v6n-zabnp {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M2 32c0 13.1 8.4 24.2 20 28.3V3.7C10.4 7.8 2 18.9 2 32");
}

.whl4uslhs {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M62 32c0-13.1-8.3-24.2-20-28.3v56.6C53.7 56.2 62 45.1 62 32");
}

</style>
