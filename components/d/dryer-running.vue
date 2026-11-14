<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vafuwv2cn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dryer-running" /></template>
<style>
.vafuwv2cn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M15.125 1.75h-6.25q-2.123 0-3.624 1.501T3.75 6.875v10.25q0 2.123 1.501 3.624t3.624 1.501h6.25q2.123 0 3.624-1.501t1.501-3.624V6.875q0-2.123-1.501-3.624T15.125 1.75M7.26 4q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141q.014.072.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-.01q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T6.5 4.75t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T7.25 4zm1.204 6.714Q9.929 9.25 12 9.25t3.536 1.464T17 14.25t-1.464 3.536Q14.071 19.25 12 19.25t-3.536-1.464Q7 16.321 7 14.25t1.464-3.536");
}

</style>
