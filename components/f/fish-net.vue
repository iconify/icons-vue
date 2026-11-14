<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gn0o9kgys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fish-net" /></template>
<style>
.gn0o9kgys {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.25 9.5q0-3.21 2.27-5.48T14 1.75t5.48 2.27t2.27 5.48t-2.27 5.48T14 17.25q-2.829 0-4.927-1.762L3.53 21.03q-.105.106-.243.163T3 21.25t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l5.542-5.543Q6.25 12.329 6.25 9.5m3.607-.386q1.361-2.269 3.59-2.332q1.873-.054 2.968 1.493L17.47 7.22q.052-.053.113-.094t.13-.069t.141-.043T18 7q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.106.105.163.243t.057.287v3.5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043T18 12q-.149 0-.287-.057t-.243-.163l-1.055-1.055q-1.095 1.547-2.968 1.493q-2.229-.063-3.59-2.332q-.053-.088-.08-.186t-.027-.2t.027-.2t.08-.186");
}

</style>
