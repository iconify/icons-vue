<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idoy8qb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:age-restricted" /></template>
<style>
.idoy8qb-a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752M8.22 6.47q.105-.106.243-.163t.287-.057t.287.057t.243.163t.163.243T9.5 7v10q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T8 17V8.811l-.72.719q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.106-.105-.163-.243T6 9t.057-.287t.163-.243zm6.53-.22q3 0 3 3q0 1.393-.647 2.14q1.147.856 1.147 2.86q0 3.5-3.5 3.5t-3.5-3.5q0-2.004 1.147-2.86q-.647-.747-.647-2.14q0-3 3-3");
}

</style>
