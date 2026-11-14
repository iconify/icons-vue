<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n2q7c3rnn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:enamel-mug" /></template>
<style>
.n2q7c3rnn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.5 3.75H3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T3 5.25h.25V17q0 3.25 3.25 3.25H14q3.25 0 3.25-3.25v-1.75H18q3.25 0 3.25-3.25v-1.5q0-3.25-3.25-3.25h-.75v-2h.25q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014m-1.75 1.5V17q0 1.75-1.75 1.75H6.5q-1.75 0-1.75-1.75V5.25zm2.25 8.5h-.75v-5H18q1.75 0 1.75 1.75V12q0 1.75-1.75 1.75");
}

</style>
