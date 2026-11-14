<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vu2x752wm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:blocked" /></template>
<style>
.vu2x752wm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M17.03 3.231q-.988-.989-2.386-.989H9.356q-1.398 0-2.386.989L3.231 6.97q-.989.988-.989 2.386v5.288q0 1.398.989 2.386l3.739 3.739q.988.989 2.386.989h5.288q1.398 0 2.386-.989l3.739-3.739q.989-.988.989-2.386V9.356q0-1.398-.989-2.386zm.5 13.239q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094l-10-10q-.053-.052-.094-.113t-.069-.13t-.043-.141T6.25 7t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T7 6.25t.146.014q.073.015.141.043t.13.069q.061.041.113.094z");
}

</style>
