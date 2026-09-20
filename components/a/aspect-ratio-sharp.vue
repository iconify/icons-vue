<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s94swzbfk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:aspect-ratio-sharp" /></template>
<style>
.s94swzbfk {
  fill: currentColor;
  d: path("M14.5 16.5h4v-4h-1v3h-3zm-9-5h1v-3h3v-1h-4zM3 19V5h18v14z");
}

</style>
