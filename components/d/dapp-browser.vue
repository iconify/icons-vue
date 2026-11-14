<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_-y5rbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dapp-browser" /></template>
<style>
.c_-y5rbho {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 2.25h10.25q2.123 0 3.624 1.501t1.501 3.624V8q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-19q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q1.75 7.926 1.75 8v-.625q0-2.123 1.501-3.624T6.875 2.25M1.75 8q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T22.25 8v8.625q0 2.123-1.501 3.624t-3.624 1.501H6.875q-2.123 0-3.624-1.501T1.75 16.625zm7 2.25q-2.5 0-2.5 2.5v3.5q0 1.036.732 1.768t1.768.732h6.5q1.036 0 1.768-.732t.732-1.768v-3.5q0-2.5-2.5-2.5z");
}

</style>
