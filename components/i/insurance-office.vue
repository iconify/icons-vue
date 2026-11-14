<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r97s-cr1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:insurance-office" /></template>
<style>
.r97s-cr1o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m3.661 8.896l6.75-5.559q1.589-1.307 3.178 0l6.75 5.559q.911.75.911 1.93v8.424q0 1.036-.732 1.768t-1.768.732H5.25q-1.036 0-1.768-.732T2.75 19.25v-8.424q0-1.18.911-1.93m4.273.288Q6.25 10.868 6.25 13.25q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043T7 14h4.25v2.75q0 .75-.75.75t-.75-.75q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T9 16t-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146Q8.25 19 10.5 19t2.25-2.25V14H17q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146q0-2.382-1.684-4.066T12 7.5T7.934 9.184");
}

</style>
