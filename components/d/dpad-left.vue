<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n-0shhb4e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dpad-left" /></template>
<style>
.n-0shhb4e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.25 1.75h-4.5q-2.5 0-2.5 2.5v2q0 1-1 1h-2q-1.036 0-1.768.732T1.75 9.75v4.5q0 2.5 2.5 2.5h2q1 0 1 1v2q0 1.036.732 1.768t1.768.732h4.5q1.036 0 1.768-.732t.732-1.768v-2q0-1 1-1h2q1.036 0 1.768-.732t.732-1.768v-4.5q0-1.036-.732-1.768T19.75 7.25h-2q-1 0-1-1v-2q0-2.5-2.5-2.5M5.811 12l1.969 1.97q.106.105.163.243T8 14.5t-.057.287t-.163.243q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-2.5-2.5q-.106-.105-.163-.243T4 12t.057-.287t.163-.243l2.5-2.5q.052-.053.113-.094t.13-.069t.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243T8 9.5t-.057.287t-.163.243z");
}

</style>
