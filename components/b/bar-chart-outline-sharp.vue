<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfd-n5unw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bar-chart-outline-sharp" /></template>
<style>
.xfd-n5unw {
  fill: currentColor;
  d: path("M16 19v-4.808h3V19zm-5.5 0V5h3v14zM5 19V9.808h3V19z");
}

</style>
