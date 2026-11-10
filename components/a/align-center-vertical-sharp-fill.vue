<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cwbro1ehx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-center-vertical-sharp-fill" /></template>
<style>
.cwbro1ehx {
  fill: currentColor;
  d: path("M13 1V3H16C16.552 3 17 3.448 17 4V10C17 10.552 16.552 11 16 11H13V13H20C20.552 13 21 13.448 21 14V20C21 20.552 20.552 21 20 21H13V23H11V21H4C3.448 21 3 20.552 3 20V14C3 13.448 3.448 13 4 13H11V11H8C7.448 11 7 10.552 7 10V4C7 3.448 7.448 3 8 3H11V1H13Z");
}

</style>
