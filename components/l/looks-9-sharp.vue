<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3crwgblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:looks-9-sharp" /></template>
<style>
.b3crwgblo {
  fill: currentColor;
  d: path("M4 20V4h16v16zm6.5-3.5h4v-9h-5v5h4v3h-3zm3-5h-3v-3h3z");
}

</style>
