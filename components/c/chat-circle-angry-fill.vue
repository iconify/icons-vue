<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qmv4exb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-circle-angry-fill" /></template>
<style>
.qmv4exb9u {
  fill: currentColor;
  d: path("M2.954 16.131A9.946 9.946 0 0 1 19.032 4.968A9.945 9.945 0 0 1 7.869 21.046l-4.673.935a1 1 0 0 1-1.177-1.177Zm5.493-8.025a1 1 0 1 0-.894 1.788l2 1a1 1 0 1 0 .894-1.788Zm8 1.788a1 1 0 1 0-.894-1.788l-2 1a1 1 0 1 0 .894 1.788Zm-6.951 2.937a6.6 6.6 0 0 0-2.203 1.462a.999.999 0 1 0 1.414 1.414A4.64 4.64 0 0 1 12 14.343a4.64 4.64 0 0 1 3.293 1.364a.999.999 0 1 0 1.414-1.414a6.6 6.6 0 0 0-2.203-1.462A6.6 6.6 0 0 0 12 12.343a6.6 6.6 0 0 0-2.504.488");
}

</style>
