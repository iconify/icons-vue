<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="su_r-ciom"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:arrow-return-down" /></template>
<style>
.su_r-ciom {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 9.5V15q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T6.25 15V9.5q0-3.75 3.75-3.75t3.75 3.75v8.189l-2.72-2.719q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113l4 4q.105.106.243.163t.287.057q.148 0 .285-.056t.242-.16l.003-.004l4-4q.106-.105.163-.243t.057-.287t-.057-.287t-.163-.243q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094l-2.72 2.719V9.5q0-2.175-1.538-3.712Q12.175 4.25 10 4.25T6.288 5.788Q4.75 7.325 4.75 9.5");
}

</style>
