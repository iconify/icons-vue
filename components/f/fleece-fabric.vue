<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aasaiogkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:fleece-fabric" /></template>
<style>
.aasaiogkx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M14.5 2.75H3q-.074 0-.146.014q-.073.015-.141.043t-.13.069t-.113.094q-.053.052-.094.113t-.069.13t-.043.141q-.014.072-.014.146V19q0 .122.038.237q.039.116.112.213q1.35 1.8 2.85 1.8q1.171 0 2.25-1.096q1.079 1.096 2.25 1.096T12 20.154q1.079 1.096 2.25 1.096t2.25-1.096q1.079 1.096 2.25 1.096q1.5 0 2.85-1.8q.073-.097.112-.213q.038-.115.038-.237v-9q0 .074-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014q-7.25 0-7.25-7.25q0-.074.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043q.072-.014.146-.014m.531.22q.105.106.162.243q.057.138.057.287q0 5.75 5.75 5.75q.149 0 .287.057t.243.163z");
}

</style>
