<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ziazvb_0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:looks-4-sharp" /></template>
<style>
.ziazvb_0a {
  fill: currentColor;
  d: path("M4 20V4h16v16zm9.5-3.5h1v-9h-1v4h-3v-4h-1v5h4z");
}

</style>
