<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yldk0zbky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dopamine" /></template>
<style>
.yldk0zbky {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m10.128 6.286l3.25 1.882q.185.107.34.232l2.654-1.548q.086-.05.182-.076t.196-.026t.196.026t.182.076l3 1.75q.085.05.154.119q.069.07.118.155q.049.086.075.181t.025.193v3.25q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T19 12.5V9.681l-2.25-1.313l-2.281 1.331q.031.199.031.416v3.77q0 1.297-1.122 1.947l-3.25 1.882q-1.128.654-2.256 0l-3.25-1.882Q3.5 15.182 3.5 13.885v-3.77q0-1.297 1.122-1.947l3.25-1.882q1.128-.653 2.256 0M6.25 12q0 2.75 2.75 2.75T11.75 12T9 9.25T6.25 12");
}

</style>
