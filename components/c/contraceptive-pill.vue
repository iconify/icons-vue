<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ic12qlg2p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:contraceptive-pill" /></template>
<style>
.ic12qlg2p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.25 3.75h7.5q2.485 0 4.243 1.757Q21.75 7.265 21.75 9.75v4.5q0 2.485-1.757 4.243q-1.758 1.757-4.243 1.757h-7.5q-2.485 0-4.243-1.757Q2.25 16.735 2.25 14.25v-4.5q0-2.485 1.757-4.243Q5.765 3.75 8.25 3.75M7 6.75Q4.75 6.75 4.75 9T7 11.25T9.25 9T7 6.75M9.75 9q0 2.25 2.25 2.25T14.25 9T12 6.75T9.75 9M17 6.75q-2.25 0-2.25 2.25T17 11.25T19.25 9T17 6.75M4.75 15q0 2.25 2.25 2.25T9.25 15T7 12.75T4.75 15M12 12.75q-2.25 0-2.25 2.25T12 17.25T14.25 15T12 12.75M14.75 15q0 2.25 2.25 2.25T19.25 15T17 12.75T14.75 15");
}

</style>
