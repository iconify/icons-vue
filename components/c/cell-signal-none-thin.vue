<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="ttpjlkb2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:cell-signal-none-thin" /></template>
<style>
.ttpjlkb2a {
  fill: currentColor;
  d: path("M44 192v8a4 4 0 0 1-8 0v-8a4 4 0 0 1 8 0");
}

</style>
