<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tfv3gxbch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-data-bar-16-regular" /></template>
<style>
.tfv3gxbch {
  fill: currentColor;
  d: path("M2 11V5a2 2 0 0 1 2-2h8a2 2 0 0 1 2 2v3a2 2 0 0 0-1-1.732V5a1 1 0 0 0-1-1H4a1 1 0 0 0-1 1v.74l5 2.692l2.132-1.148A2 2 0 0 0 10 8v.491l-1.763.95a.5.5 0 0 1-.474 0L3 6.875V11a1 1 0 0 0 1 1h3v1H4a2 2 0 0 1-2-2m10-4a1 1 0 0 0-1 1v7a1 1 0 1 0 2 0V8a1 1 0 0 0-1-1m3 2a1 1 0 0 0-1 1v5a1 1 0 1 0 2 0v-5a1 1 0 0 0-1-1m-7 3a1 1 0 1 1 2 0v3a1 1 0 1 1-2 0z");
}

</style>
