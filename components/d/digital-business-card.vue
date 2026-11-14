<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd17xtwvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:digital-business-card" /></template>
<style>
.xd17xtwvo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 4.25h10.25q2.123 0 3.624 1.501t1.501 3.624v5.25q0 2.123-1.501 3.624t-3.624 1.501H6.875q-2.123 0-3.624-1.501T1.75 14.625v-5.25q0-2.123 1.501-3.624T6.875 4.25M17 7.75h-2.75Q12 7.75 12 10v4q0 .932.659 1.591t1.591.659H17q.932 0 1.591-.659T19.25 14v-4q0-2.25-2.25-2.25m-10.24.5h-.01q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T6 9t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141Q7.51 9.074 7.51 9t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
