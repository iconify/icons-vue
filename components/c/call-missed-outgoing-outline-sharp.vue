<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nhwi2lbkc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:call-missed-outgoing-outline-sharp" /></template>
<style>
.nhwi2lbkc {
  fill: currentColor;
  d: path("M11.904 16.714L3.98 8.79l.708-.714l7.215 7.215l6.388-6.388H13v-1h7v7h-1V9.617z");
}

</style>
