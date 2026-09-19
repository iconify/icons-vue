<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="a5np3_q7m"/><path class="j02cc9blg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:free-button" /></template>
<style>
.a5np3_q7m {
  fill: var(--svg-color--4fd1d9, #4fd1d9);
  d: path("M62 52c0 5.5-4.5 10-10 10H12C6.5 62 2 57.5 2 52V12C2 6.5 6.5 2 12 2h40c5.5 0 10 4.5 10 10z");
}

.j02cc9blg {
  fill: var(--svg-color--fff, #fff);
  d: path("M34 41h8v-3h-5.1v-4.5H42v-3h-5.1V26H42v-3h-8zm20-15v-3h-8v18h8v-3h-5.1v-4.5H54v-3h-5.1V26zM23.9 41v-7.5H25l2.5 7.5h3l-2.6-7.9c1.8-.8 3.1-2.7 3.1-4.9c0-2.9-2.2-5.2-5-5.2h-5v18zm0-15H26c1.2 0 2.1 1 2.1 2.2s-1 2.2-2.1 2.2h-2.1zm-11 15v-7.5H18v-3h-5.1V26H18v-3h-8v18z");
}

</style>
