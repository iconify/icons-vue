<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i99qk9buo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:looks-two-sharp" /></template>
<style>
.i99qk9buo {
  fill: currentColor;
  d: path("M9.5 16.5h5v-1h-4v-3h4v-5h-5v1h4v3h-4zM4 20V4h16v16z");
}

</style>
