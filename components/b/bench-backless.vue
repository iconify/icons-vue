<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zo0y2lfxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bench-backless" /></template>
<style>
.zo0y2lfxa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20 6.25H4q-2.25 0-2.25 2.25T4 10.75h.75V17q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014t.146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141T6.25 17v-2.25h11.5V17q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-6.25H20q2.25 0 2.25-2.25T20 6.25m-2.25 7H6.25v-2.5h11.5z");
}

</style>
