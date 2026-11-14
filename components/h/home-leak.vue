<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd1nt9ber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:home-leak" /></template>
<style>
.bd1nt9ber {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 8.75q-2.121 0-2.243-2H2.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141Q1.75 6.074 1.75 6t.014-.146t.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h7.257q.122-2 2.243-2q2.123 0 2.243 2.004Q17.75 5.373 17.75 9v3q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T16.25 12V9q0-2.125-2.008-2.243Q14.118 8.75 12 8.75m4.443 5.748q.026-.029.055-.055q.111-.1.252-.15q.14-.05.289-.042t.284.072t.234.175Q20 17.212 20 19.001q-.002 2.997-3 2.997T14 19q0-1.788 2.443-4.502");
}

</style>
