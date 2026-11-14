<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ks-hllb_o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:humidity-control" /></template>
<style>
.ks-hllb_o {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 2.75q-.149 0-.287.057t-.243.163Q4.75 9.689 4.75 14.5q0 3.003 2.123 5.127T12 21.75t5.127-2.123q2.123-2.124 2.123-5.127q0-4.811-6.72-11.53q-.105-.106-.243-.163T12 2.75m2.5 11.5q.074 0 .146.014q.073.015.141.043t.13.069t.113.094q.053.052.094.113t.069.13t.043.141t.014.146t-.014.146q-.015.073-.043.141t-.069.13t-.094.113q-.052.053-.113.094t-.13.069t-.141.043t-.146.014h-5q-.074 0-.146-.014q-.073-.015-.141-.043t-.13-.069t-.113-.094q-.053-.052-.094-.113t-.069-.13t-.043-.141T8.75 15t.014-.146q.015-.073.043-.141t.069-.13t.094-.113q.052-.053.113-.094t.13-.069t.141-.043t.146-.014z");
}

</style>
