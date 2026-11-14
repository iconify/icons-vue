<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oh3a3jbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ban-hammer" /></template>
<style>
.oh3a3jbeo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m15.884 4.288l2.828 2.828q.952.952.952 2.298t-.952 2.298t-2.298.952t-2.298-.952l-.884-.883L8.03 16.03q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113l5.201-5.202l-.883-.884q-.952-.952-.952-2.298t.952-2.298t2.298-.952t2.298.952M5 17.75h8q2.25 0 2.25 2.25T13 22.25H5q-2.25 0-2.25-2.25T5 17.75");
}

</style>
