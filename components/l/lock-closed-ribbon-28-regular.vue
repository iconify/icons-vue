<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="s7z2e7bnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-closed-ribbon-28-regular" /></template>
<style>
.s7z2e7bnv {
  fill: currentColor;
  d: path("M25 26.3a.7.7 0 0 1-1.133.55L21.5 24.99l-2.367 1.86A.7.7 0 0 1 18 26.3v-3.557A5.48 5.48 0 0 0 21.5 24c1.33 0 2.55-.472 3.5-1.257zM14 2a5.5 5.5 0 0 1 5.5 5.5v2.509a3.75 3.75 0 0 1 3.459 3.187A5.5 5.5 0 0 0 21.5 13l-.13.003a2.25 2.25 0 0 0-2.12-1.503H8.75a2.25 2.25 0 0 0-2.25 2.25v8.5a2.25 2.25 0 0 0 2.25 2.25H17V26H8.75A3.75 3.75 0 0 1 5 22.25v-8.5a3.75 3.75 0 0 1 3.5-3.741V7.5A5.5 5.5 0 0 1 14 2m7.5 12a4.5 4.5 0 1 1-3.5 7.33l-.007-.01A4.5 4.5 0 0 1 21.5 14M14 16.5a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m0-13a4 4 0 0 0-4 4V10h8V7.5a4 4 0 0 0-4-4");
}

</style>
