<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b6czx-hhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:curtains-sharp-fill" /></template>
<style>
.b6czx-hhm {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M22 4H21V21C21 21.552 20.552 22 20 22H13V4H11V22H4C3.448 22 3 21.552 3 21V4H2V2H22V4ZM7 4V10H9V4H7ZM15 4V10H17V4H15Z");
}

</style>
