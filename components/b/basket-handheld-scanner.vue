<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yjnbat14e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:basket-handheld-scanner" /></template>
<style>
.yjnbat14e {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M20.5 11.25q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-7q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014t-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v7q0 .074.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014m-6.5-8H4q-2.25 0-2.25 2.25v3q0 2.25 2.25 2.25h1.853l-1.591 8.868q-.012.065-.012.132q0 .828.586 1.414t1.414.586h1.23q1.67.084 2.228-1.501q.017-.05.027-.102l1.88-9.397H15q2.75 0 2.75-2.75V7q0-3.75-3.75-3.75");
}

</style>
