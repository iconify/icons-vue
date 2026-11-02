<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="csyaspbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fullscreen-fill-sharp" /></template>
<style>
.csyaspbko {
  fill: currentColor;
  d: path("M2 3a1 1 0 0 1 1-1h5a1 1 0 0 1 0 2H4v4a1 1 0 0 1-2 0Zm19-1a1 1 0 0 1 1 1v5a1 1 0 0 1-2 0V4h-4a1 1 0 0 1 0-2ZM3 22a1 1 0 0 1-1-1v-5a1 1 0 0 1 2 0v4h4a1 1 0 0 1 0 2Zm19-1a1 1 0 0 1-1 1h-5a1 1 0 0 1 0-2h4v-4a1 1 0 0 1 2 0Z");
}

</style>
