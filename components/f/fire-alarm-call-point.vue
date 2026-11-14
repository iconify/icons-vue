<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jnft26b4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fire-alarm-call-point" /></template>
<style>
.jnft26b4u {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.625 2.25h12.75q1.398 0 2.386.989q.989.988.989 2.386v12.75q0 3.375-3.375 3.375H5.625q-1.398 0-2.386-.989q-.989-.988-.989-2.386V5.625q0-1.398.989-2.386q.988-.989 2.386-.989m2.663 4.538Q6.75 8.325 6.75 10.5t1.538 3.712Q9.825 15.75 12 15.75t3.712-1.538q1.538-1.537 1.538-3.712t-1.538-3.712Q14.175 5.25 12 5.25T8.288 6.788M16.25 18q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-7q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141T7.75 18q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h7q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146");
}

</style>
