<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kh_hox5uy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:desktop-app-dev" /></template>
<style>
.kh_hox5uy {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.875 2.25h10.25q2.123 0 3.624 1.501t1.501 3.624v4.75q0 2.123-1.501 3.624t-3.624 1.501H12.75v2.5H16q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H8q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.074.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043T8 19.75h3.25v-2.5H6.875q-2.123 0-3.624-1.501T1.75 12.125v-4.75q0-2.123 1.501-3.624T6.875 2.25m9.375 3h-8.5q-2.5 0-2.5 2.5v4q0 2.5 2.5 2.5h8.5q1.036 0 1.768-.732t.732-1.768v-4q0-1.036-.732-1.768T16.25 5.25");
}

</style>
