<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pi06xzvhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:banknote-download" /></template>
<style>
.pi06xzvhp {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18 2.75H6q-1.76 0-3.005 1.245T1.75 7v3q0 1.76 1.245 3.005T6 14.25h12q1.76 0 3.005-1.245T22.25 10V7q0-1.76-1.245-3.005T18 2.75M12 5.5q3 0 3 3t-3 3t-3-3t3-3m.53 16.53l-.003.004q-.105.104-.242.16T12 22.25t-.287-.057t-.243-.163l-2.75-2.75q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.105-.106.243-.163T9.25 18t.287.057t.243.163l1.47 1.469V16.25q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T12 15.5t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v3.439l1.47-1.469q.105-.106.243-.163T14.75 18t.287.057t.243.163q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113z");
}

</style>
