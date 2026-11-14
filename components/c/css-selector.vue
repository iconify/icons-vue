<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxkg6ccwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:css-selector" /></template>
<style>
.zxkg6ccwp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 1.75h6.25q2.123 0 3.624 1.501t1.501 3.624v4.829q-.708-.204-1.5-.204q-2.175 0-3.712 1.538Q11.5 14.575 11.5 16.75q0 .792.204 1.5H6.875q-2.123 0-3.624-1.501T1.75 13.125v-6.25q0-2.123 1.501-3.624T6.875 1.75m9.875 11q-4 0-4 4t4 4q1.47 0 2.399-.54l1.821 1.82q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-1.82-1.821q.54-.929.54-2.399q0-4-4-4m0 6.5q-2.5 0-2.5-2.5t2.5-2.5t2.5 2.5t-2.5 2.5m0-3.75q.512 0 .815.21q-.329.552-.816 1.039t-1.039.816q-.21-.303-.21-.815q0-1.25 1.25-1.25");
}

</style>
