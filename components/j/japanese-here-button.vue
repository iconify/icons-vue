<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="a5np3_q7m"/><path class="hcx6-wb8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:japanese-here-button" /></template>
<style>
.a5np3_q7m {
  fill: var(--svg-color--4fd1d9, #4fd1d9);
  d: path("M62 52c0 5.5-4.5 10-10 10H12C6.5 62 2 57.5 2 52V12C2 6.5 6.5 2 12 2h40c5.5 0 10 4.5 10 10z");
}

.hcx6-wb8d {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.1 47v-6.4h10.3V23.2H14.1V17H30v30zm20 0v-6.4h10.3V23.2H34.1V17H50v30z");
}

</style>
