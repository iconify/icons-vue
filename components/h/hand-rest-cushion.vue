<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0mwmxbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hand-rest-cushion" /></template>
<style>
.u0mwmxbmb {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 5.625q-5.247 0-8.737 1.163q-.142.048-.254.145q-.113.098-.18.232q-1.668 3.335 0 6.67q.067.134.18.232q.112.097.254.145q3.49 1.163 8.737 1.163t8.737-1.163q.142-.048.254-.145q.113-.098.18-.232q1.668-3.335 0-6.67q-.067-.134-.18-.232q-.112-.097-.254-.145Q17.247 5.625 12 5.625M22.25 17.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014h-19q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h19q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146");
}

</style>
