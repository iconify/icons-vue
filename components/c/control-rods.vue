<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lglqk72uq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:control-rods" /></template>
<style>
.lglqk72uq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6 2.25h12q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T18 3.75h-1.25v4.5H17q1.76 0 3.005 1.245T21.25 12.5V18q0 1.76-1.245 3.005T17 22.25H7q-1.76 0-3.005-1.245T2.75 18v-5.5q0-1.76 1.245-3.005T7 8.25h.25v-4.5H6q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T5.25 3t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043Q5.926 2.25 6 2.25m9.25 6v-4.5h-2.5v4.5zm-6.5-4.5h2.5v4.5h-2.5z");
}

</style>
