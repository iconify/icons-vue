<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k1tn4z3lt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:jump-start" /></template>
<style>
.k1tn4z3lt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21.5 8.25h-19q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141Q1.75 8.926 1.75 9t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T22.25 9t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014m-3 4.749q0-.828.585-1.414q.586-.586 1.415-.586t1.415.586t.585 1.414q.001.829-.585 1.416q-.586.586-1.415.586t-1.415-.586t-.585-1.414zM1.5 13q0-.829.586-1.414Q2.671 11 3.5 11t1.414.586Q5.5 12.172 5.5 13t-.586 1.414Q4.329 15 3.5 15t-1.414-.586Q1.5 13.829 1.5 13m6.25-2q-2 0-2 2t2 2t2-2t-2-2M10 13q0-2 2-2t2 2t-2 2t-2-2m6.25-2q-2 0-2 2t2 2t2-2t-2-2");
}

</style>
