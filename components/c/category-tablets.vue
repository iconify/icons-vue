<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eq5s1jnpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:category-tablets" /></template>
<style>
.eq5s1jnpc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.5 4.25h13q1.76 0 3.005 1.245T22.75 8.5v7q0 1.76-1.245 3.005T18.5 19.75h-13q-1.76 0-3.005-1.245T1.25 15.5v-7q0-1.76 1.245-3.005T5.5 4.25m13.51 7H19q-.074 0-.146.014q-.073.015-.141.043t-.13.069q-.061.041-.113.094q-.053.052-.094.113t-.069.13t-.043.141t-.014.146t.014.146q.015.073.043.141t.069.13t.094.113q.052.053.113.094t.13.069t.141.043t.146.014h.01q.074 0 .146-.014q.073-.015.141-.043t.13-.069t.113-.094q.053-.052.094-.113t.069-.13t.043-.141q.014-.072.014-.146t-.014-.146q-.015-.073-.043-.141t-.069-.13t-.094-.113q-.052-.053-.113-.094t-.13-.069t-.141-.043t-.146-.014");
}

</style>
