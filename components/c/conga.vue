<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dk3h5lkbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:conga" /></template>
<style>
.dk3h5lkbo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.753 4.881Q5.887 2.25 12 2.25t6.247 2.631q2.414 8.176-1.564 16.929q-.045.099-.116.18q-.07.082-.161.141t-.194.089q-.104.03-.212.03H8q-.108 0-.212-.03q-.103-.031-.194-.089q-.091-.059-.161-.141t-.116-.18Q3.339 13.057 5.753 4.881m.62 5.151q-.281 5.225 2.114 10.718h7.026q2.395-5.493 2.114-10.718q-5.627 1.94-11.254 0m.142-1.542q5.485 2.015 10.97 0q-.111-.849-.294-1.692q-1.514.952-5.191.952t-5.191-.952q-.183.843-.294 1.692");
}

</style>
