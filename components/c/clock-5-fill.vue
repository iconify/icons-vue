<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="z7csbubqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-5-fill" /></template>
<style>
.z7csbubqo {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C18.0751 1 23 5.9249 23 12C23 18.0751 18.0751 23 12 23C5.9249 23 1 18.0751 1 12C1 5.9249 5.9249 1 12 1ZM11 6L11 12C11 12.1755 11.0462 12.348 11.134 12.5L13.634 16.8301C13.7666 17.0598 13.985 17.2274 14.2412 17.296C14.4974 17.3647 14.7703 17.3287 15 17.1961C15.4783 16.92 15.6422 16.3084 15.366 15.8301L13 11.732L13 6C13 5.4477 12.5523 5 12 5C11.4477 5 11 5.4477 11 6Z");
}

</style>
