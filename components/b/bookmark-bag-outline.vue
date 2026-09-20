<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w3nonvb4g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bookmark-bag-outline" /></template>
<style>
.w3nonvb4g {
  fill: currentColor;
  d: path("M11.413 14.087q.164-.164.164-.414v-.211h.827v.211q0 .25.163.414t.413.163t.413-.163t.165-.414v-.212q.36 0 .603-.243q.243-.244.243-.604v-3.39q0-.36-.243-.6t-.603-.24h-.231V7.347q0-.36-.243-.603T12.48 6.5h-.98q-.36 0-.603.243t-.243.603v1.038h-.231q-.36 0-.603.244t-.243.604v3.39q0 .36.243.601t.603.24v.21q0 .25.163.414t.413.163t.413-.163m.011-5.702V7.268h1.135v1.115zM6 19.5V5.616q0-.691.463-1.153T7.616 4h8.769q.69 0 1.153.463T18 5.616V19.5l-6-2.577zm1-1.55l5-2.15l5 2.15V5.616q0-.231-.192-.424T16.384 5H7.616q-.231 0-.424.192T7 5.616zM7 5h10z");
}

</style>
