<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3dan_itw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:command-vehicle" /></template>
<style>
.w3dan_itw {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7.75 7.75V2.5q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146v5.25h2.625q2.905 0 3.309 2.5H18.5q.164 0 .313.069q.15.068.256.193l3 3.5q.088.102.134.228t.047.26v3q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-1.438q.188.531.188 1.25q0 2.75-2.75 2.75t-2.75-2.75q0-.719.188-1.25H14.5q-.105 0-.205-.029q-.101-.028-.19-.083t-.159-.133t-.117-.171q-.769.416-1.954.416H9.562q.188.531.188 1.25q0 2.75-2.75 2.75T4.25 19.5q0-.744.202-1.287q-2.702-.318-2.702-3.338v-3.75q0-1.398.989-2.386q.988-.989 2.386-.989zm9.75 9h3.25v-1.973l-2.595-3.027H15.25v3.125q0 1.125-.375 1.875z");
}

</style>
