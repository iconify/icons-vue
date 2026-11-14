<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g1w26-bda"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:cargo-ship" /></template>
<style>
.g1w26-bda {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M6.5 8.75h1q1.5 0 2 1q.5-1 2-1h1q.932 0 1.591.659q.213.213.357.454q.469-1.113 2.052-1.113h1q2.25 0 2.25 2.25v2.5q0 .413-.076.75H21q.074 0 .146.014q.073.015.141.043t.13.069q.061.041.113.094q.053.052.094.113t.069.13t.043.141t.014.146q0 .162-.067.31l-2.5 5.5q-.045.099-.116.18q-.07.082-.161.141t-.194.089q-.104.03-.212.03h-13q-.108 0-.212-.03q-.103-.031-.194-.089q-.091-.059-.161-.141t-.116-.18l-2.5-5.5q-.062-.135-.067-.285t.048-.288q.052-.14.154-.249t.238-.171q.148-.067.31-.067h1.326q-.076-.337-.076-.75V11q0-2.25 2.25-2.25");
}

</style>
