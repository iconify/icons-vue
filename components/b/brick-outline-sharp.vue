<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vkv3-obtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:brick-outline-sharp" /></template>
<style>
.vkv3-obtp {
  fill: currentColor;
  d: path("M2 20V8h3V4h6v4h2V4h6v4h3v12zm2-2h16v-8H4zM7 8h2V6H7zm8 0h2V6h-2zM4 18h16zM7 8h2zm8 0h2z");
}

</style>
