<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mp1_s0buq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:genre-folk" /></template>
<style>
.mp1_s0buq {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M11.5 1.75h1q.932 0 1.591.659T14.75 4t-.659 1.591q-.569.569-1.341.647V9.79q2.11.231 3.669 1.791Q18.25 13.411 18.25 16t-1.831 4.419T12 22.25t-4.419-1.831Q5.75 18.589 5.75 16t1.831-4.419q1.559-1.56 3.669-1.791V6.243q-2-.122-2-2.243q0-2.25 2.25-2.25m2.5 15h-4q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h4q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T14 16.75");
}

</style>
