<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dyb_byx3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:align-flex-center-outline-sharp" /></template>
<style>
.dyb_byx3u {
  fill: currentColor;
  d: path("M11 22v-8.5H3v-3h8V2h2v8.5h8v3h-8V22z");
}

</style>
