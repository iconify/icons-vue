<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yh7_r4-yq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:blood-pressure-check" /></template>
<style>
.yh7_r4-yq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.727 3.727Q2.75 5.704 2.75 8.5t1.977 4.773q1.723 1.723 4.068 1.944q.431 3.292 5.013 3.517q.21 1.294 1.187 2.271Q16.24 22.25 18 22.25t3.005-1.245T22.25 18t-1.245-3.005T18 13.75t-3.005 1.245q-.964.963-1.181 2.235q-3.029-.18-3.484-2.026q2.266-.254 3.943-1.931Q16.25 11.296 16.25 8.5t-1.977-4.773T9.5 1.75T4.727 3.727M11.72 5.22q.105-.106.243-.163T12.25 5t.287.057t.243.163q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113l-2.75 2.75q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T8.75 8.5t.014-.146q.015-.073.043-.141t.069-.13t.094-.113z");
}

</style>
