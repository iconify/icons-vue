<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sxwggo-mg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:campus-hiring" /></template>
<style>
.sxwggo-mg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m12.75 6.625l5.7 4.275q.07.052.126.119t.095.146t.059.163t.02.172v10q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H6q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-10q0-.087.02-.172t.059-.163q.039-.079.095-.146t.126-.119l5.7-4.275V2q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014q.088 0 .174.02q.085.021.164.06q.078.04.146.097t.119.127q.376-.083.792.021l1.287.322q1.057.263 1.057 1.353t-1.058 1.353l-1.286.322q-.335.084-.645.046zM12 11.5q-4 0-4 4t4 4t4-4q0-1.657-1.172-2.828Q13.657 11.5 12 11.5");
}

</style>
