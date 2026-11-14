<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fj7prxtxa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bike-computer" /></template>
<style>
.fj7prxtxa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13.625 2.25h-3.25q-2.123 0-3.624 1.501T5.25 7.375v5.25q0 2.123 1.501 3.624t3.624 1.501h.875v2H2.5q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-8.75v-2h.875q2.123 0 3.624-1.501t1.501-3.624v-5.25q0-2.123-1.501-3.624T13.625 2.25m-2.875 3h2.5q1.036 0 1.768.732t.732 1.768v2.5q0 1.036-.732 1.768t-1.768.732h-2.5q-1.036 0-1.768-.732T8.25 10.25v-2.5q0-2.5 2.5-2.5");
}

</style>
