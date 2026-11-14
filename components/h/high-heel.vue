<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oo96nxcfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:high-heel" /></template>
<style>
.oo96nxcfe {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 17q0 2.75 2.25 2.75h4q2.393 0 6.214-4.234q3.175-3.519 4.837-3.766h.699v8.75q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014q.074 0 .146-.014q.073-.015.141-.043t.13-.069q.061-.041.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146v-8.793q.11-.039.202-.109t.16-.165t.103-.206t.035-.227V5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13q-.041-.061-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043T21 4.25h-1.5q-1.401 0-3.834 3.527Q11.891 13.25 9 13.25H5.5q-3.75 0-3.75 3.75");
}

</style>
