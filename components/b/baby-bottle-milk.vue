<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyiuslblm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:baby-bottle-milk" /></template>
<style>
.vyiuslblm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75q-2.498 0-2.727 3.506Q7.25 5.366 7.25 7.5q0 1.39.859 1.922q-.183.154-.358.329q-1.501 1.501-1.501 3.624v3.75q0 2.123 1.501 3.624t3.624 1.501h1.25q2.123 0 3.624-1.501t1.501-3.624v-3.75q0-2.123-1.501-3.624q-.175-.175-.358-.329q.859-.532.859-1.922q0-2.134-2.023-2.244Q14.498 1.75 12 1.75m5.75 12.75q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H7q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T7 13.75h10q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146M12 3.25q1.066 0 1.223 2h-2.446q.157-2 1.223-2");
}

</style>
