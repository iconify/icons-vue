<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nh7tghr1e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:field-sample" /></template>
<style>
.nh7tghr1e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 2.25h7q2.25 0 2.25 2.25T15.5 6.75h-7q-2.25 0-2.25-2.25T8.5 2.25M13.625 8h-3.25Q8.252 8 6.751 9.501T5.25 13.125v4q0 2.123 1.501 3.624t3.624 1.501h3.25q2.123 0 3.624-1.501t1.501-3.624v-4q0-2.123-1.501-3.624T13.625 8M8.25 18q0-4.75 3.75-4.75T15.75 18q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H9q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T8.25 18");
}

</style>
