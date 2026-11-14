<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbzw5fb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fuel-octane" /></template>
<style>
.lbzw5fb1o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11 2.25H7q-1.76 0-3.005 1.245T2.75 6.5V18q0 1.76 1.245 3.005T7 22.25h4q1.76 0 3.005-1.245T15.25 18v-3.75H16q.75 0 .75.75v3q0 2.5 2.5 2.5t2.5-2.5V8q0-.149-.057-.287t-.163-.243l-2.5-2.5q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.106.105-.163.243t-.057.287t.057.287t.163.243l2.28 2.281V18q0 1-1 1t-1-1v-3q0-2.25-2.25-2.25h-.75V6.5q0-1.76-1.245-3.005T11 2.25m-.53 4.47q.105-.106.243-.163T11 6.5t.287.057t.243.163q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113l-2 2q-.052.053-.113.094t-.13.069t-.141.043T9 10t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.106-.105-.163-.243T8.25 9.25t.057-.287t.163-.243z");
}

</style>
