<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjf8w1b8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:bold" /></template>
<style>
.sjf8w1b8o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M13 3.75H7q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146v15q0 .074.014.146q.015.073.043.141t.069.13q.041.061.094.113q.052.053.113.094t.13.069t.141.043t.146.014h7q1.864 0 3.182-1.318T18.5 15.75t-1.318-3.182q-.575-.575-1.254-.899q.13-.113.254-.237Q17.5 10.114 17.5 8.25t-1.318-3.182T13 3.75m-5.25 9H14q3 0 3 3q0 1.243-.879 2.121q-.878.879-2.121.879H7.75zm5.25-1.5H7.75v-6H13q3 0 3 3q0 1.243-.879 2.121q-.878.879-2.121.879");
}

</style>
