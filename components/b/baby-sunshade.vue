<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfx98fsfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baby-sunshade" /></template>
<style>
.wfx98fsfp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.459 4.459Q2.75 7.169 2.75 11q0 5.75 9.25 5.75T21.25 11q0-4.099 1.166-4.876q.124-.083.207-.207t.112-.27q.03-.146.001-.293q-.029-.146-.112-.27q-.041-.061-.093-.114q-.052-.052-.114-.093q-.061-.041-.129-.07q-.068-.028-.141-.042t-.146-.015t-.147.014q-.072.015-.14.043t-.13.069q-1.689 1.126-1.823 5.374H12.75V2.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q12.074 1.75 12 1.75q-3.831 0-6.541 2.709m5.791 5.791H4.282Q4.52 7.52 6.52 5.52t4.73-2.238zm-3.75 7q-2.5 0-2.5 2.5t2.5 2.5q1.036 0 1.768-.732T10 19.75t-.732-1.768T7.5 17.25m6.5 2.5q0-2.5 2.5-2.5t2.5 2.5t-2.5 2.5t-2.5-2.5");
}

</style>
