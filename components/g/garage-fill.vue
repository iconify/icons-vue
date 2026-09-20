<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="hugf_jbtv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:garage-fill" /></template>
<style>
.hugf_jbtv {
  fill: currentColor;
  d: path("M240 192h-8V98.67a16 16 0 0 0-7.12-13.31l-88-58.67a16 16 0 0 0-17.75 0l-88 58.67A16 16 0 0 0 24 98.67V192h-8a8 8 0 0 0 0 16h224a8 8 0 0 0 0-16m-104-64h56v24h-56Zm-16 24H64v-24h56Zm-56 16h56v24H64Zm72 0h56v24h-56Z");
}

</style>
