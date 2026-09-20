<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x2kxjbbon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-comment-sharp" /></template>
<style>
.x2kxjbbon {
  fill: currentColor;
  d: path("M11 14h2v-3h3V9h-3V6h-2v3H8v2h3zm-9 8V2h20v16H6z");
}

</style>
