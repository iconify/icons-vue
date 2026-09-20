<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rlzkpovle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-strikethrough-sharp" /></template>
<style>
.rlzkpovle {
  fill: currentColor;
  d: path("M3 13.48v-1h18v1zm8.385-2.96V6.25H6.019V5H18v1.25h-5.365v4.27zm0 8.48v-3.558h1.25V19z");
}

</style>
