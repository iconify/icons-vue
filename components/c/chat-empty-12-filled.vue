<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="gula3vbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chat-empty-12-filled" /></template>
<style>
.gula3vbxz {
  fill: currentColor;
  d: path("M6 1a5 5 0 0 0-4.386 7.403l-.592 1.947a.5.5 0 0 0 .624.624l1.945-.592A5 5 0 1 0 6 1");
}

</style>
