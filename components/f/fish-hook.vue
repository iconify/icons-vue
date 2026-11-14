<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bbwoz4beg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fish-hook" /></template>
<style>
.bbwoz4beg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M16 1.5q-2.5 0-2.5 2.5q0 2.092 1.75 2.433V15.5q0 4-4 4t-4-4v-2.689l1.22 1.219q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113l-2.5-2.5q-.105-.106-.243-.163T6.5 10.25q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141T5.75 11v4.5q0 2.278 1.611 3.889T11.25 21t3.889-1.611T16.75 15.5V6.433Q18.5 6.092 18.5 4q0-2.5-2.5-2.5");
}

</style>
