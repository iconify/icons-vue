<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="evs37vbul"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cheque-mobile-deposit" /></template>
<style>
.evs37vbul {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.375 4.25h11.25q2.123 0 3.624 1.501t1.501 3.624v5.25q0 2.123-1.501 3.624t-3.624 1.501H6.375q-2.123 0-3.624-1.501T1.25 14.625v-5.25q0-2.123 1.501-3.624T6.375 4.25M16.25 7h-8q-2.5 0-2.5 2.5v5q0 1.036.732 1.768T8.25 17h8q1.036 0 1.768-.732t.732-1.768v-5q0-1.036-.732-1.768T16.25 7M4.26 11.25h-.01q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q3.5 11.926 3.5 12t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069q.068.028.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141q.014-.072.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
