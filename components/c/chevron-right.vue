<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar9i-vb-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:chevron-right" /></template>
<style>
.ar9i-vb-a {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m9.53 4.97l6.5 6.5q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113l-6.5 6.5q-.105.106-.243.163T9 19.25t-.287-.057t-.243-.163q-.053-.052-.094-.113t-.069-.13t-.043-.141t-.014-.146t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113L14.439 12L8.47 6.03q-.053-.052-.094-.113t-.069-.13t-.043-.141T8.25 5.5t.014-.146q.015-.073.043-.141t.069-.13q.041-.061.094-.113q.105-.106.243-.163T9 4.75t.287.057t.243.163");
}

</style>
