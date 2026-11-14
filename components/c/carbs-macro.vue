<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mgf9zsbjt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:carbs-macro" /></template>
<style>
.mgf9zsbjt {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 4.5q0-3 2.25-3q1.023 0 1.685.993q.565.848.565 2.007q0 1.461-.533 2.21q.438-.21 1.033-.21q2.25 0 2.25 3q0 1.5-.562 2.25Q17 12.5 17 14q0 3-2.25 3q-1.5 0-2-1.333V21.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146v-5.833Q10.75 17 9.25 17Q7 17 7 14q0-1.5.563-2.25Q7 11 7 9.5q0-3 2.25-3q.595 0 1.033.21q-.533-.749-.533-2.21m3 7.833q.125-.333.313-.583q-.188-.25-.313-.583zm-1.5-4.934q-.149-.045-.283-.109q.168.236.283.543zm1.5.434q.115-.307.283-.543q-.134.064-.283.109zm-1.812 3.917q.187-.25.312-.583v1.166q-.125-.333-.312-.583");
}

</style>
