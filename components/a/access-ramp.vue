<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjrqgpb6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:access-ramp" /></template>
<style>
.hjrqgpb6a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m7.45 16.1l-2.2 1.65h15v-7.5h-5l-1.8 1.35zm6.3-6.6l.8-.6q.097-.073.213-.112q.115-.038.237-.038h6q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146v8.293q.11.039.202.109t.16.165t.103.206t.035.227q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-19q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014h.25l3.5-2.625V11.5q0-.087.02-.172t.059-.163q.039-.079.095-.146t.126-.119l6-4.5q.119-.09.264-.127q.144-.037.292-.015t.276.097t.218.195q.073.097.112.213q.038.115.038.237zm-6 4.5l4.5-3.375V8.5l-4.5 3.375z");
}

</style>
