<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ofhl5yb3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:e-mobiledata-badge-sharp" /></template>
<style>
.ofhl5yb3q {
  fill: currentColor;
  d: path("M8.885 16.5h6.23v-1h-5.23v-3h4.23v-1h-4.23v-3h5.23v-1h-6.23zM4 20V4h16v16z");
}

</style>
