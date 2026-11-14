<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="js7-e8bqi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dead-stock" /></template>
<style>
.js7-e8bqi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.53 2.47l18 18q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-18-18q-.053-.052-.094-.113t-.069-.13t-.043-.141T2.25 3t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q2.926 2.25 3 2.25t.146.014q.073.015.141.043t.13.069t.113.094m17.22 7.655v7.797L5.078 2.25H19.25q1.243 0 2.121.879q.879.878.879 2.121q0 2.41-1.936 2.884q.436.777.436 1.991M19.111 21.94L1.808 4.636q-.058.295-.058.614q0 2.41 1.936 2.884q-.436.777-.436 1.991v8.75q0 3.375 3.375 3.375h10.75q1.023 0 1.736-.31");
}

</style>
