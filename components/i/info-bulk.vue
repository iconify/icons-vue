<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ebt7lcckq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:info-bulk" /></template>
<style>
.ebt7lcckq {
  fill: currentColor;
  d: path("M12.01 5a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2ZM13 18a1 1 0 0 1-2 0v-8a1 1 0 0 1 2 0Z");
}

</style>
