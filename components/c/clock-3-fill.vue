<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="g4ex10bfa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-3-fill" /></template>
<style>
.g4ex10bfa {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C18.0751 1 23 5.9249 23 12C23 18.0751 18.0751 23 12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1ZM11 6L11 12C11 12.5523 11.4477 13 12 13L17 13C17.5523 13 18 12.5523 18 12C18 11.4477 17.5523 11 17 11L13 11L13 6C13 5.4477 12.5523 5 12 5C11.4477 5 11 5.4477 11 6Z");
}

</style>
