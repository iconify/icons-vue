<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n1ox_2bwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:eject" /></template>
<style>
.n1ox_2bwu {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m10.057 4.708l-4.832 5.969q-.992 1.226-.313 2.649t2.256 1.424h9.664q1.577 0 2.256-1.424t-.313-2.649l-4.832-5.969q-.751-.927-1.943-.927t-1.943.927M3.5 18.75h17q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-17q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014");
}

</style>
