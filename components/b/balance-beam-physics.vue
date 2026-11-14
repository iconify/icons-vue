<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ix8co1b7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:balance-beam-physics" /></template>
<style>
.ix8co1b7s {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M7 5.75H5.5q-.932 0-1.591.659T3.25 8v2q0 .413.076.75H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-.826q.076-.337.076-.75V8q0-2.25-2.25-2.25H17q-2.25 0-2.25 2.25v2q0 .413.076.75H9.174q.076-.337.076-.75V8q0-2.25-2.25-2.25m3.018 7.848q.637-1.184 1.981-1.184t1.981 1.184l.988 1.835q.605 1.124-.049 2.22t-1.931 1.097H11.01q-1.277-.001-1.931-1.097t-.049-2.219z");
}

</style>
