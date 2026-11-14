<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghp_xac7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chimney-stack" /></template>
<style>
.ghp_xac7a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.411 8.169q-2.015-1.02-1.204-3.128q.698-1.815 2.411-1.627q.901-1.324 2.632-1.324q1.893 0 2.794 1.583q1.306.658 1.306 2.202q0 1.693-1.572 2.321q-.134.054-.278.054h-5.75q-.179 0-.339-.081M5 3.75h3.5q2.25 0 2.25 2.25q0 1.5-1 2v13.5q0 .074-.014.146q-.015.073-.043.141t-.069.13q-.041.061-.094.113q-.052.053-.113.094t-.13.069t-.141.043T9 22.25H4.5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069q-.061-.041-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146V8q-1-.5-1-2q0-2.25 2.25-2.25m.25 4.5v12.5h3V8.25z");
}

</style>
