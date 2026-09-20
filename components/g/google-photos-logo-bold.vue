<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="vtqymefyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:google-photos-logo-bold" /></template>
<style>
.vtqymefyc {
  fill: currentColor;
  d: path("M232 116h-33.36A76 76 0 0 0 128 12a12 12 0 0 0-12 12v33.36A76 76 0 0 0 12 128a12 12 0 0 0 12 12h33.36A76 76 0 0 0 128 244a12 12 0 0 0 12-12v-33.36A76 76 0 0 0 244 128a12 12 0 0 0-12-12m-52-28a51.4 51.4 0 0 1-8.18 28H140V37.4A52.09 52.09 0 0 1 180 88M88 76a51.4 51.4 0 0 1 28 8.18V116H37.4A52.09 52.09 0 0 1 88 76m-12 92a51.4 51.4 0 0 1 8.18-28H116v78.6A52.09 52.09 0 0 1 76 168m92 12a51.4 51.4 0 0 1-28-8.18V140h78.6a52.09 52.09 0 0 1-50.6 40");
}

</style>
