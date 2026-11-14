<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oaou2ok2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:carpenter-pencil" /></template>
<style>
.oaou2ok2r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m18.01 3.515l2.475 2.475q.733.732.733 1.767q0 1.036-.733 1.768l-6.718 6.717q-1.084 1.083-2.167.838q-.254 1.002-1.224 1.455l-2.41 1.125q-1.427.666-2.542-.447l-.636-.637q-1.114-1.115-.448-2.542l1.125-2.41q.453-.97 1.455-1.224q-.246-1.083.837-2.167l6.718-6.718q.732-.733 1.767-.733q1.036 0 1.768.733M8.287 17.127l-1.414-1.414q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113l1.414 1.414q.105.106.243.163t.287.057t.287-.057t.243-.163q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113");
}

</style>
