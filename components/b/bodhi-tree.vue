<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oo6_386ef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bodhi-tree" /></template>
<style>
.oo6_386ef {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2 11q0 3.25 3 3.25h4.75v2.939L6.97 19.97q-.053.052-.094.113t-.069.13t-.043.141t-.014.146q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.105.106.243.163t.287.057t.287-.057t.243-.163l3-3q.106-.105.163-.243t.057-.287v-3.25h1.5v3.25q0 .149.057.287t.163.243l3 3q.105.106.243.163t.287.057t.287-.057t.243-.163q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113l-2.78-2.781V14.25H19q2.932 0 3.246-2.984q.275-2.615-1.899-3.331q.393-3.497-2.71-4.986q-2.847-1.367-5.14.128q-2.205-1.399-5.031.07q-2.903 1.51-3.186 4.656Q2 8.166 2 11");
}

</style>
