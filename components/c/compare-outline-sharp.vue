<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="edzctfb7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:compare-outline-sharp" /></template>
<style>
.edzctfb7d {
  fill: currentColor;
  d: path("M11 22.23V20H4V4h7V1.77h1v20.46zM5 18h6v-7.192zm9 2v-8l5 6V5h-5V4h6v16z");
}

</style>
