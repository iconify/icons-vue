<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a3l2glbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:binary-code" /></template>
<style>
.a3l2glbnv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m6.97 3.47l-2.5 2.5q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043T5 7.25t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094l1.22-1.219V20q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T8.25 20V4q0-.149-.057-.287T8.03 3.47q-.052-.053-.113-.094t-.13-.069t-.141-.043T7.5 3.25t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094M11.25 12q0-3.491 1.251-5.992Q13.88 3.25 16 3.25t3.499 2.758Q20.75 8.509 20.75 12t-1.251 5.992Q18.12 20.75 16 20.75t-3.499-2.758Q11.25 15.491 11.25 12");
}

</style>
