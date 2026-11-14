<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jlgt_wbca"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:leaf-cluster" /></template>
<style>
.jlgt_wbca {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.25 17.157q-6.948-1.072-8.97-7.945q-.044-.15-.024-.305q.018-.148.092-.278q.074-.129.192-.221q.117-.092.261-.131t.292-.021q3.44.43 5.947 2.678q-.463-4.271 2.32-8.825q.039-.063.089-.117t.109-.098q.06-.044.127-.075t.139-.048t.146-.02q.073-.003.146.008q.073.012.143.037q.069.026.132.064q.155.094.249.249q2.783 4.554 2.32 8.825q2.507-2.248 5.947-2.678q.073-.009.147-.004t.145.025t.137.053t.124.078t.107.101t.085.12t.06.135q.023.07.032.143q.02.155-.024.305q-2.022 6.873-8.97 7.945V21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146z");
}

</style>
