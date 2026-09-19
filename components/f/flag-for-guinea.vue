<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="g8mrvvbeu"/><path class="wfb3q1y3f"/><path class="v62jlcbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-guinea" /></template>
<style>
.g8mrvvbeu {
  fill: var(--svg-color--75a843, #75a843);
  d: path("M62 32c0 13.1-8.3 24.2-20 28.3V3.7C53.7 7.8 62 18.9 62 32");
}

.v62jlcbzg {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M42 60.3c-3.1 1.1-6.5 1.7-10 1.7s-6.9-.6-10-1.7V3.7C25.1 2.6 28.5 2 32 2s6.9.6 10 1.7z");
}

.wfb3q1y3f {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M2 32C2 18.9 10.4 7.8 22 3.7v56.6C10.4 56.2 2 45.1 2 32");
}

</style>
