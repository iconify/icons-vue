<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvyz03bdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:dwell-select" /></template>
<style>
.hvyz03bdt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1.75q4.246 0 7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12q0-.149.057-.287t.163-.243q.105-.106.243-.163t.287-.057q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141q.014.072.014.146q0 3.624 2.563 6.187T12 20.75t6.187-2.563T20.75 12t-2.563-6.187T12 3.25q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m0 5q-4.025 0-6.66 4.894q-.044.082-.067.173T5.25 12t.023.183t.067.173Q7.975 17.25 12 17.25t6.66-4.894q.044-.082.067-.173T18.75 12t-.023-.183t-.067-.173Q16.025 6.75 12 6.75M9.5 12q0-2.5 2.5-2.5q1.036 0 1.768.732T14.5 12t-.732 1.768T12 14.5q-2.5 0-2.5-2.5");
}

</style>
