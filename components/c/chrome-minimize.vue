<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kayxdc_nz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:chrome-minimize" /></template>
<style>
.kayxdc_nz {
  fill: currentColor;
  d: path("M4 20v-2h16v2H4Z");
}

</style>
