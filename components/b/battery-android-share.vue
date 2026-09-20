<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iav9nacgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-share" /></template>
<style>
.iav9nacgm {
  fill: currentColor;
  d: path("M4 18q-1.25 0-2.125-.875T1 15V9q0-1.25.875-2.125T4 6h14.175l-3 3q-1.725 0-2.95 1.113T11 13v5zm15-2l-1.425-1.425l1.6-1.575H15v3h-2v-3q0-.825.588-1.412T15 11h4.175L17.6 9.4L19 8l4 4z");
}

</style>
