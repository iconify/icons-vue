<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nok-i6cwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:kiosk-24-filled" /></template>
<style>
.nok-i6cwo {
  fill: currentColor;
  d: path("M6.25 2A2.25 2.25 0 0 0 4 4.25v6.5A2.25 2.25 0 0 0 6.25 13H9.5v7.5H7.75a.75.75 0 0 0 0 1.5h8.5a.75.75 0 0 0 0-1.5H14.5V13h3.25A2.25 2.25 0 0 0 20 10.75v-6.5A2.25 2.25 0 0 0 17.75 2zM11 20.5V13h2v7.5z");
}

</style>
