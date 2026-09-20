<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y9hg0kg8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:lte-mobiledata-badge-sharp" /></template>
<style>
.y9hg0kg8t {
  fill: currentColor;
  d: path("M5.154 15.5h4v-1h-3v-6h-1zm5.577 0h1v-6h2v-1h-5v1h2zm4.769 0h4v-1h-3v-2h2v-1h-2v-2h3v-1h-4zM2 20V4h20v16z");
}

</style>
