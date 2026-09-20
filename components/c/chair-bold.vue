<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="qkbbk9b7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:chair-bold" /></template>
<style>
.qkbbk9b7h {
  fill: currentColor;
  d: path("M208 128h-28v-20h12a20 20 0 0 0 20-20V40a20 20 0 0 0-20-20H64a20 20 0 0 0-20 20v48a20 20 0 0 0 20 20h12v20H48a20 20 0 0 0-20 20v24a20 20 0 0 0 20 20h8v32a12 12 0 0 0 24 0v-32h96v32a12 12 0 0 0 24 0v-32h8a20 20 0 0 0 20-20v-24a20 20 0 0 0-20-20M68 44h120v40H68Zm32 64h56v20h-56Zm104 60H52v-16h152Z");
}

</style>
