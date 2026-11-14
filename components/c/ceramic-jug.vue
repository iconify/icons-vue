<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q5qyp-bps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:ceramic-jug" /></template>
<style>
.q5qyp-bps {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14 2.75H5q-.093 0-.182.023q-.09.022-.172.066q-.082.043-.15.106q-.069.062-.12.139q-.041.061-.069.13q-.028.068-.043.14t-.014.147q0 .074.015.146q.014.073.042.141t.07.129t.093.114q.053.052.114.093L7.25 5.901v.189q-3.5 2.391-3.5 8.41q0 7.25 5.75 7.25h3q5.75 0 5.75-7.25q0-.458-.02-.895q2.56-.723 2.52-3.605V8.5q0-3.75-3.75-3.75h-2.25V3.5q0-.074-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043Q14.074 2.75 14 2.75M19.25 10q.021 1.535-1.165 2.056q-.571-3.924-3.11-5.806H17q2.25 0 2.25 2.25z");
}

</style>
