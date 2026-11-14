<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r59wslape"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:few-shot" /></template>
<style>
.r59wslape {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.744 17.75q-.083 1.6-1.239 2.755Q16.26 21.75 14.5 21.75H6q-1.76 0-3.005-1.245T1.75 17.5V13q0-1.76 1.245-3.005q.971-.971 2.255-1.185V5.5q0-2.75 2.75-2.75h11.5q2.75 0 2.75 2.75V15q0 2.75-2.75 2.75zm-11.994-9V5.5q0-1.25 1.25-1.25h11.5q1.25 0 1.25 1.25V15q0 1.25-1.25 1.25h-.75V13q0-1.76-1.245-3.005T14.5 8.75zm5.75 5.75H6q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043T6 16h6.5q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
