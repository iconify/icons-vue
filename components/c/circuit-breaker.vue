<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uba5g6q_p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:circuit-breaker" /></template>
<style>
.uba5g6q_p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.875 1.75h8.25q2.123 0 3.624 1.501t1.501 3.624v10.25q0 2.123-1.501 3.624t-3.624 1.501h-8.25q-2.123 0-3.624-1.501T2.75 17.125V6.875q0-2.123 1.501-3.624T7.875 1.75m3.375 9.532q-2.75.296-2.75 3.343v.75q0 3.375 3.375 3.375h.25q3.375 0 3.375-3.375v-.75q0-3.047-2.75-3.343V6.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T12 5.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146z");
}

</style>
