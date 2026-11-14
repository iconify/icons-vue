<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e4phhey1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-phones" /></template>
<style>
.e4phhey1l {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.125 1.75h-2.25q-2.123 0-3.624 1.501T5.75 6.875v10.25q0 2.123 1.501 3.624t3.624 1.501h2.25q2.123 0 3.624-1.501t1.501-3.624V6.875q0-2.123-1.501-3.624T13.125 1.75m.375 16q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-3q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
