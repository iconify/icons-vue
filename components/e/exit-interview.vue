<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l61ruy3dr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:exit-interview" /></template>
<style>
.l61ruy3dr {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4.75 2.25h4.5q1.036 0 1.768.732t.732 1.768v15q0 1.036-.732 1.768t-1.768.732h-4.5q-1.036 0-1.768-.732T2.25 19.75v-15q0-2.5 2.5-2.5m10.5 1H20q2.25 0 2.25 2.25V11q0 .932-.659 1.591T20 13.25h-3.21l-2.535 2.305q-.111.1-.251.151t-.29.043t-.284-.071t-.235-.173q-.094-.104-.145-.235Q13 15.14 13 15V5.5q0-2.25 2.25-2.25m-7 8.25q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141t.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014z");
}

</style>
