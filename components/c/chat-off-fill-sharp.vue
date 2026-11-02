<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exe9ljbqw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-off-fill-sharp" /></template>
<style>
.exe9ljbqw {
  fill: currentColor;
  d: path("m4.414 2l18.293 18.293a.999.999 0 1 1-1.414 1.414L17.586 18H7.414l-3.707 3.707A1 1 0 0 1 2 21V3c0-.176.046-.348.134-.5a1 1 0 0 1 1.573-1.207ZM22 16.757L7.243 2H21a1 1 0 0 1 1 1Z");
}

</style>
