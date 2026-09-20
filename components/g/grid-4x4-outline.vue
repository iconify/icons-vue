<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i3gvhvb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:grid-4x4-outline" /></template>
<style>
.i3gvhvb0m {
  fill: currentColor;
  d: path("M5 22v-3H2v-2h3v-4H2v-2h3V7H2V5h3V2h2v3h4V2h2v3h4V2h2v3h3v2h-3v4h3v2h-3v4h3v2h-3v3h-2v-3h-4v3h-2v-3H7v3zm2-5h4v-4H7zm6 0h4v-4h-4zm-6-6h4V7H7zm6 0h4V7h-4z");
}

</style>
