<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zjptzqr8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:docs-outline-sharp" /></template>
<style>
.zjptzqr8a {
  fill: currentColor;
  d: path("m14 2l5 5v15H5V2zm-3 2H7v16h10V10h-6zm2 0v4h4v-.175L13.175 4zM9 19v-2h4v2zm0-4v-2h6v2z");
}

</style>
