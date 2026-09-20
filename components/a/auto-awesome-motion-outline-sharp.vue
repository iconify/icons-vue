<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w4r7n9cag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:auto-awesome-motion-outline-sharp" /></template>
<style>
.w4r7n9cag {
  fill: currentColor;
  d: path("M11 21V11h10v10zm1-1h8v-8h-8zm-5-2.77V7h10.23v1H8v9.23zm-4-4V3h10.23v1H4v9.23zM12 20v-8z");
}

</style>
