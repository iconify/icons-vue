<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b5rffkbka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-fill-sharp" /></template>
<style>
.b5rffkbka {
  fill: currentColor;
  d: path("M12.707 22.707a1 1 0 0 1-1.414 0l-10-10a1 1 0 0 1 0-1.414l10-10a1 1 0 0 1 1.414 0l10 10a1 1 0 0 1 0 1.414Z");
}

</style>
