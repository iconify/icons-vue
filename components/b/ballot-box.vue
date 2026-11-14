<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j4xrwwbie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ballot-box" /></template>
<style>
.j4xrwwbie {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16.75 10.75H17q1.76 0 3.005 1.245T21.25 15v3q0 1.76-1.245 3.005T17 22.25H7q-1.76 0-3.005-1.245T2.75 18v-3q0-1.76 1.245-3.005T7 10.75h.25V3.5q0-1.75 1.75-1.75h6q1.75 0 1.75 1.75zm-8 0h6.5V3.5q0-.25-.25-.25H9q-.25 0-.25.25zm2.75-3.561l-.72-.719q-.105-.106-.243-.163t-.287-.057t-.287.057t-.243.163q-.053.052-.094.113t-.069.13t-.043.141T9.5 7t.014.146q.015.073.043.141t.069.13q.041.061.094.113l1.25 1.25q.105.106.243.163T11.5 9t.287-.057t.243-.163l2.25-2.25q.053-.052.094-.113t.069-.13t.043-.141T14.5 6t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.105-.106-.243-.163t-.287-.057t-.287.057t-.243.163z");
}

</style>
