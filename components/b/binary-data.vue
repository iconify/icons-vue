<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mat1xdbuz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:binary-data" /></template>
<style>
.mat1xdbuz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m6.47 3.47l-2.5 2.5q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094l1.22-1.219V20q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T7.75 20V4q0-.149-.057-.287T7.53 3.47t-.243-.163T7 3.25t-.287.057t-.243.163M9.75 12q0-3.51 1.414-6.025Q12.697 3.25 15 3.25t3.836 2.725Q20.25 8.49 20.25 12t-1.414 6.025Q17.303 20.75 15 20.75t-3.836-2.725Q9.75 15.51 9.75 12");
}

</style>
