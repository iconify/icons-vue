<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj-3t3_ii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:content-plan" /></template>
<style>
.wj-3t3_ii {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 1.75h7q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v5q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h5q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v12q0 2.75-2.75 2.75H7q-2.75 0-2.75-2.75v-15q0-1.139.805-1.945Q5.861 1.75 7 1.75m7.531.22l4.999 5q-.105-.106-.243-.163T19 6.75h-4.25V2.5q0-.149-.057-.287t-.162-.243M7.25 11.5q0 1.837 1.5 2.174V17q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h2.826q.337 1.5 2.174 1.5q2.25 0 2.25-2.25t-2.25-2.25q-1.837 0-2.174 1.5H10.25v-2.576q1.5-.337 1.5-2.174q0-2.25-2.25-2.25T7.25 11.5");
}

</style>
