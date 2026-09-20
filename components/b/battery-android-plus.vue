<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tg_7gubdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-android-plus" /></template>
<style>
.tg_7gubdy {
  fill: currentColor;
  d: path("M4 18q-1.25 0-2.125-.875T1 15V9q0-1.25.875-2.125T4 6h12v3h-3v6h3v3zm14-2v-3h-3v-2h3V8h2v3h3v2h-3v3z");
}

</style>
