<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gii-66bpc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-view-comfy" /></template>
<style>
.gii-66bpc {
  fill: currentColor;
  d: path("M2 4v7h20V4zm8 16h12v-7H10zm-8 0h6v-7H2z");
}

</style>
