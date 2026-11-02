<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o7b8kgbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-up-left-large-fill" /></template>
<style>
.o7b8kgbbx {
  fill: currentColor;
  d: path("m8.414 7l10.293 10.293a.999.999 0 1 1-1.414 1.414L7 8.414V14a1 1 0 0 1-2 0V6a1 1 0 0 1 1-1h8a1 1 0 0 1 0 2Z");
}

</style>
