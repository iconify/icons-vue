<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ey7s3mbuq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:earbuds" /></template>
<style>
.ey7s3mbuq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.818 5.318Q2.5 6.636 2.5 8.5t1.318 3.182q.436.436.932.728v7.09q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-6.557Q6.613 13 7 13q1.864 0 3.182-1.318T11.5 8.5t-1.318-3.182T7 4T3.818 5.318M12.5 8.5q0-1.864 1.318-3.182T17 4t3.182 1.318T21.5 8.5t-1.318 3.182q-.436.436-.932.728v7.09q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-6.557Q17.387 13 17 13q-1.864 0-3.182-1.318T12.5 8.5");
}

</style>
