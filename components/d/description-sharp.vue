<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h8qu4kb_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:description-sharp" /></template>
<style>
.h8qu4kb_r {
  fill: currentColor;
  d: path("M8.5 17.5h7v-1h-7zm0-4h7v-1h-7zM5 21V3h9.5L19 7.5V21zm9-13h4l-4-4z");
}

</style>
