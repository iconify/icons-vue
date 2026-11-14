<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="piqfh-btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:courtroom" /></template>
<style>
.piqfh-btz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m14.53 4.434l3.536 3.536q.952.952.952 2.298t-.952 2.298t-2.298.952t-2.298-.952l-1.238-1.237L4.53 19.03q-.105.106-.243.163T4 19.25t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l7.701-7.702L9.934 9.03q-.952-.952-.952-2.298t.952-2.298t2.298-.952t2.298.952M14 16.75h5q2.25 0 2.25 2.25T19 21.25h-5q-2.25 0-2.25-2.25T14 16.75");
}

</style>
