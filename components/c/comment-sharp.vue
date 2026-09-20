<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="crobjxbuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:comment-sharp" /></template>
<style>
.crobjxbuy {
  fill: currentColor;
  d: path("M6 14h12v-2H6zm0-3h12V9H6zm0-3h12V6H6zM2 18V2h20v20l-4-4z");
}

</style>
