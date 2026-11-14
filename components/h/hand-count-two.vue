<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj_2s622w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hand-count-two" /></template>
<style>
.gj_2s622w {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 12.04V15q0 7.25 7.25 7.25q2.983 0 4.858-1.985Q18.75 18.261 18.75 15v-2.5q0-.062-.01-.123q-.32-1.917-1.961-2.573q-1.146-.458-2.908-.222l.623-4.989q.015-.121-.009-.24q-.342-1.715-2.071-1.981T9.843 3.639q-.054.098-.077.208l-.483 2.318l-.288-1.514q-.199-2.45-2.673-2.273q-2.498.178-2.32 2.675l.002.027zM15 13.75q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H9.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
