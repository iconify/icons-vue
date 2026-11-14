<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0x1ju_yv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fuel-farm" /></template>
<style>
.c0x1ju_yv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M22.75 18.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014H2q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146q0-.116.035-.227t.103-.206q.067-.095.16-.165q.092-.07.202-.109V10.5q0-2.625 3.125-2.625T8 10.5v4.25h1V7.5q0-2.625 3-2.625T15 7.5v7.25h1V10.5q0-2.625 3.125-2.625T22.25 10.5v7.293q.11.039.202.109t.16.165t.103.206t.035.227M16 16.25h-1v1.5h1zm-2.5-.75v-8q0-1.125-1.5-1.125T10.5 7.5v10.25h3zm-4.5.75H8v1.5h1zm-2.5-.75v-5q0-1.125-1.625-1.125T3.25 10.5v7.25H6.5zm14.25 2.25V10.5q0-1.125-1.625-1.125T17.5 10.5v7.25z");
}

</style>
