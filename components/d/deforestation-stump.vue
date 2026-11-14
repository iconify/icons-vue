<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7uenb1ha"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:deforestation-stump" /></template>
<style>
.c7uenb1ha {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.25 7.499q.001-1.913 2.465-3.145Q8.923 3.25 12 3.25t5.285 1.104Q19.75 5.587 19.75 7.5v10q0 1.189 1.28 2.47q.106.105.163.243t.057.287q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-17q-.149 0-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q1.28-1.281 1.28-2.47zm4 .001q0-1.75 3.75-1.75t3.75 1.75T12 9.25T8.25 7.5m-2.5 2.571V17.5q0 1.143-.685 2.25h13.87q-.685-1.107-.685-2.25v-7.429q-.423.304-.965.575Q15.077 11.75 12 11.75t-5.285-1.104q-.542-.271-.965-.575");
}

</style>
