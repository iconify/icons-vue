<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="auylm0bxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:bar-chart" /></template>
<style>
.auylm0bxp {
  fill: currentColor;
  d: path("M49.501 8.249L38.251 20.75h-5l-11.25 12.499H17l-11.25 12.5V2H2v60h60V8.249zM27.626 56.375h-9.688V35.124h9.688zm16.25 0h-9.688v-33.75h9.688zm16.249 0h-9.687V10.124h9.687z");
}

</style>
