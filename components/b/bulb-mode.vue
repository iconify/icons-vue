<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tx-vnv9iu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bulb-mode" /></template>
<style>
.tx-vnv9iu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.25 12q-.001 4.039 2.855 6.896T12 21.753t6.895-2.857T21.75 12q.001-4.039-2.855-6.896T12 2.247q-4.04 0-6.895 2.857Q2.249 7.961 2.25 12m6.25 0V7q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h3q3.25 0 3.25 3.25q0 1.469-.664 2.274Q16 12.555 16 14.5q0 3.25-3.25 3.25h-3.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T8.5 17zm1.5.75v3.5h2.75q1.75 0 1.75-1.75t-1.75-1.75zm2.25-1.5H10v-3.5h2.25Q14 7.75 14 9.5t-1.75 1.75");
}

</style>
