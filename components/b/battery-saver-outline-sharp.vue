<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ai5zq3bix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-saver-outline-sharp" /></template>
<style>
.ai5zq3bix {
  fill: currentColor;
  d: path("M16 22v-3h-3v-2h3v-3h2v3h3v2h-3v3zm-9 0V4h3V2h4v2h3v8q-.525 0-1.025.088T15 12.35V6H9v14h2.35q.2.575.488 1.075t.687.925z");
}

</style>
