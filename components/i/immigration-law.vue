<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzgokfb9j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:immigration-law" /></template>
<style>
.lzgokfb9j {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16 1.75H8q-1.76 0-3.005 1.245T3.75 6v12q0 1.76 1.245 3.005T8 22.25h8q1.76 0 3.005-1.245T20.25 18V6q0-1.76-1.245-3.005T16 1.75M6.75 10.5q0-2.175 1.538-3.712Q9.825 5.25 12 5.25t3.712 1.538Q17.25 8.325 17.25 10.5t-1.538 3.712Q14.175 15.75 12 15.75t-3.712-1.538Q6.75 12.675 6.75 10.5m9 7.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H9q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T8.25 18t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T9 17.25h6q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146");
}

</style>
