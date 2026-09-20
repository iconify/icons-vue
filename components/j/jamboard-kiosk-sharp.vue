<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="opg7qlb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:jamboard-kiosk-sharp" /></template>
<style>
.opg7qlb9k {
  fill: currentColor;
  d: path("M6 21v-2h5v-3H2V3h20v13h-9v3h5v2z");
}

</style>
