<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1dggab2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:copyleft" /></template>
<style>
.g1dggab2k {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.752 4.752Q1.75 7.754 1.75 12t3.002 7.248T12 22.25t7.248-3.002T22.25 12t-3.002-7.248T12 1.75T4.752 4.752M12 6.75q2.175 0 3.712 1.538Q17.25 9.825 17.25 12t-1.538 3.712Q14.175 17.25 12 17.25t-3.712-1.538q-.053-.052-.094-.113t-.069-.13q-.028-.068-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069q.068-.028.141-.043t.146-.014t.146.014q.073.015.141.043t.13.069t.113.094q2.652 2.651 5.304 0q2.651-2.652 0-5.304q-2.652-2.651-5.304 0q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113Q9.825 6.75 12 6.75");
}

</style>
