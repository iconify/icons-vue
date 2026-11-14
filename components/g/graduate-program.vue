<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="keh76pbvd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:graduate-program" /></template>
<style>
.keh76pbvd {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m13.006 4.664l5.646 2.823q1.134.566 1.235 1.772q.056-.009.113-.009q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v5q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014t-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T19.25 15v-3.894q-.25.233-.598.407l-.903.451l.001.036v4.5q0 .167-.071.318t-.199.258Q15.172 19 12 19t-5.48-1.924q-.128-.107-.199-.258T6.25 16.5V12l.001-.036l-.903-.451Q4.103 10.891 4.103 9.5t1.245-2.013l5.646-2.823q1.006-.503 2.012 0m-5.256 8.05v3.424Q9.557 17.5 12 17.5t4.25-1.362v-3.424l-3.244 1.622q-1.006.503-2.013 0z");
}

</style>
