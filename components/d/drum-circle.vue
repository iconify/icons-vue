<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lw8w3cczm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:drum-circle" /></template>
<style>
.lw8w3cczm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.464 3.464Q7 4.929 7 7t1.464 3.536T12 12t3.536-1.464Q17 9.071 17 7t-1.464-3.536Q14.071 2 12 2T8.464 3.464M9.75 7q0-2.25 2.25-2.25T14.25 7T12 9.25T9.75 7m-8.5 9.75q0-2.071 1.464-3.536Q4.179 11.75 6.25 11.75t3.536 1.464t1.464 3.536t-1.464 3.536Q8.321 21.75 6.25 21.75t-3.536-1.464Q1.25 18.821 1.25 16.75m12.964-3.536q-1.464 1.465-1.464 3.536t1.464 3.536q1.465 1.464 3.536 1.464t3.536-1.464q1.464-1.465 1.464-3.536t-1.464-3.536q-1.465-1.464-3.536-1.464t-3.536 1.464M6.25 14.5Q4 14.5 4 16.75T6.25 19q.932 0 1.591-.659T8.5 16.75t-.659-1.591T6.25 14.5m9.25 2.25q0-2.25 2.25-2.25T20 16.75T17.75 19t-2.25-2.25");
}

</style>
