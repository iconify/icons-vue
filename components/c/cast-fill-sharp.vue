<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d91xjqvlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cast-fill-sharp" /></template>
<style>
.d91xjqvlf {
  fill: currentColor;
  d: path("M2 7V5a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v14a1 1 0 0 1-1 1h-6a1 1 0 0 1 0-2h5V6H4v1a1 1 0 0 1-2 0m1 3a9 9 0 0 1 9 9a1 1 0 0 1-2 0a6.9 6.9 0 0 0-.55-2.724a6.9 6.9 0 0 0-1.5-2.226A6.97 6.97 0 0 0 3 12a1 1 0 0 1 0-2m0 4c1.33 0 2.597.522 3.536 1.464A5 5 0 0 1 8 19a1 1 0 0 1-2 0a2.98 2.98 0 0 0-.879-2.121A2.98 2.98 0 0 0 3 16a1 1 0 0 1 0-2m0 4h.01a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2");
}

</style>
