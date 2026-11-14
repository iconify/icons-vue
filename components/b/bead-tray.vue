<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a45fhg_7m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bead-tray" /></template>
<style>
.a45fhg_7m {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3.75 6.5q0-2.25 2.25-2.25T8.25 6.5T6 8.75T3.75 6.5M12 4.25q-2.25 0-2.25 2.25T12 8.75t2.25-2.25T12 4.25m3.75 2.25q0-2.25 2.25-2.25t2.25 2.25T18 8.75T15.75 6.5M2.5 10.25q-.105 0-.206.029q-.143.041-.26.134q-.117.092-.19.223q-.072.13-.089.278t.024.292l2 7q.017.058.042.113t.061.105q.034.05.076.094t.09.081q.049.036.103.065q.053.028.111.047q.057.019.117.029t.121.01h15q.061 0 .121-.01t.117-.029t.111-.047t.103-.065t.09-.081q.042-.044.076-.094q.035-.05.061-.105t.042-.113l2-7q.029-.101.029-.206q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014z");
}

</style>
