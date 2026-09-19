<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ijdxe0fug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-dehaze" /></template>
<style>
.ijdxe0fug {
  fill: currentColor;
  d: path("M2 15.5v2h20v-2zm0-5v2h20v-2zm0-5v2h20v-2z");
}

</style>
