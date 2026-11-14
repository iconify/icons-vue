<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfym4dnme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:junction-box" /></template>
<style>
.hfym4dnme {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.5 3.25h-5q-1.76 0-3.005 1.245T5.25 7.5v3.75H2q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h3.25v3.75q0 1.76 1.245 3.005T9.5 20.75h5q1.76 0 3.005-1.245T18.75 16.5v-3.75H22q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T22 11.25h-3.25V7.5q0-1.76-1.245-3.005T14.5 3.25m-3.75 5.5h2.5q1.036 0 1.768.732t.732 1.768v1.5q0 1.036-.732 1.768t-1.768.732h-2.5q-1.036 0-1.768-.732T8.25 12.75v-1.5q0-2.5 2.5-2.5");
}

</style>
