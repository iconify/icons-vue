<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o1zpj5b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:glassblowing-pipe" /></template>
<style>
.o1zpj5b-g {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.183 11.878L6.561 18.5l.719.72q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163l-.72-.719l-1.47 1.469q-.105.106-.243.163t-.287.057t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113l1.469-1.47l-.719-.72q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.105-.106.243-.163t.287-.057t.287.057t.243.163l.72.719l6.622-6.622q-.967-2.693.352-5.002Q13.94 3.25 17 3.25q3.75 0 3.75 3.75q0 3.06-2.565 4.526q-2.309 1.319-5.002.352");
}

</style>
