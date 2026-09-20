<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aoj0hqqtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:computer-cancel-sharp" /></template>
<style>
.aoj0hqqtd {
  fill: currentColor;
  d: path("m9.4 14.5l2.6-2.6l2.6 2.6l1.4-1.4l-2.6-2.6L16 7.9l-1.4-1.4L12 9.1L9.4 6.5L8 7.9l2.6 2.6L8 13.1zM1 21v-2h22v2zm1-3V3h20v15z");
}

</style>
