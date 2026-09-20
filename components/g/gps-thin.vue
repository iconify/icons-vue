<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="lue_g9wgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:gps-thin" /></template>
<style>
.lue_g9wgk {
  fill: currentColor;
  d: path("M240 124h-28.1A84.11 84.11 0 0 0 132 44.1V16a4 4 0 0 0-8 0v28.1A84.11 84.11 0 0 0 44.1 124H16a4 4 0 0 0 0 8h28.1a84.11 84.11 0 0 0 79.9 79.9V240a4 4 0 0 0 8 0v-28.1a84.11 84.11 0 0 0 79.9-79.9H240a4 4 0 0 0 0-8m-112 80a76 76 0 1 1 76-76a76.08 76.08 0 0 1-76 76");
}

</style>
