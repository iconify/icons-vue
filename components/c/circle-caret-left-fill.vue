<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="nd965_b6p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-caret-left-fill" /></template>
<style>
.nd965_b6p {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12 1C18.0751 1 23 5.92487 23 12C23 18.0751 18.0751 23 12 23C5.92487 23 1 18.0751 1 12C1 5.92487 5.92487 1 12 1ZM17 7.53809C16.9999 6.45591 15.9088 5.71039 14.917 6.10254L14.7207 6.19629L6.7832 10.6582C5.73886 11.2452 5.73886 12.7548 6.7832 13.3418L14.7207 17.8037C15.7588 18.3871 16.9998 17.6161 17 16.4619V7.53809Z");
}

</style>
