<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="egv9hvqtc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:density-medium-sharp" /></template>
<style>
.egv9hvqtc {
  fill: currentColor;
  d: path("M3 21v-2h18v2zm0-8v-2h18v2zm0-8V3h18v2z");
}

</style>
