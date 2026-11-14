<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ur9pp8blz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:eye-minus" /></template>
<style>
.ur9pp8blz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.75 3.75q-5.307 0-7.931 5.686q-.069.149-.069.314t.069.314Q4.443 15.75 9.75 15.75t7.931-5.686q.069-.149.069-.314t-.069-.314Q15.057 3.75 9.75 3.75m0 2.75Q13 6.5 13 9.75T9.75 13T6.5 9.75T9.75 6.5m0 5Q8 11.5 8 9.75T9.75 8t1.75 1.75t-1.75 1.75M14 17.75h7.5q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H14q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014");
}

</style>
