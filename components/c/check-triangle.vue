<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o--t9kcxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:check-triangle" /></template>
<style>
.o--t9kcxi {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.348 16.535L14.976 6.481V6.48Q14.023 4.696 12 4.696T9.024 6.481L3.651 16.535q-.901 1.686.083 3.326q.983 1.64 2.895 1.639h10.742q1.912.001 2.895-1.639t.082-3.326m-9.895.357l3.473-4.125q.048-.057.106-.103t.123-.08t.136-.054q.071-.021.145-.027q.074-.007.147.002q.073.008.144.03t.135.058t.121.083t.103.106q.046.057.08.123q.034.065.054.136q.021.071.027.145q.007.074-.002.147q-.008.073-.03.144t-.058.135t-.083.121l-4 4.75q-.021.025-.044.047q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094l-2.25-2.25q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043T8.25 15t.146.014q.073.015.141.043t.13.069t.113.094z");
}

</style>
