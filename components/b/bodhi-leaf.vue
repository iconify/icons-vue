<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bas6k5l8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bodhi-leaf" /></template>
<style>
.bas6k5l8m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 18.282q-1.832.743-4.206.064Q3.25 17.262 3.25 13q0-3.482 5.188-8.088q2.122-1.885 2.993-2.9q.048-.056.106-.102t.124-.079t.137-.053t.144-.026q.074-.005.147.003q.074.009.144.032t.135.059t.12.085q.044.037.081.081q.871 1.015 2.993 2.9Q20.75 9.518 20.75 13q0 4.262-3.794 5.346q-2.374.679-4.206-.064V7.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T12 6.75t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146z");
}

</style>
