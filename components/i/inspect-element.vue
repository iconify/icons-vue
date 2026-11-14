<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q8fz_1m6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:inspect-element" /></template>
<style>
.q8fz_1m6i {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 1.75h8.5q1.76 0 3.005 1.245T18.75 6v6.3Q17.937 12 17 12q-2.071 0-3.536 1.464Q12 14.929 12 17q0 .937.3 1.75H6q-1.76 0-3.005-1.245T1.75 14.5V6q0-1.76 1.245-3.005T6 1.75m11 11.5q-3.75 0-3.75 3.75T17 20.75q1.345 0 2.207-.482l1.763 1.762q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-1.762-1.763q.482-.862.482-2.207q0-3.75-3.75-3.75m0 6q-2.25 0-2.25-2.25T17 14.75T19.25 17T17 19.25M17 16q.961 0 .999.924q-.216.304-.494.581q-.277.278-.581.494Q16 17.961 16 17q0-1 1-1");
}

</style>
