<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikpt-5b5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:id-badge-fill-sharp" /></template>
<style>
.ikpt-5b5d {
  fill: currentColor;
  d: path("M4 3a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Zm6 2a1 1 0 0 0 0 2h4a1 1 0 0 0 0-2Zm-1 7a3 3 0 1 0 6 0a3 3 0 0 0-6 0m0 8h6a1 1 0 0 0 1-1c0-.943-.561-1.737-1.324-2.246C13.892 16.232 12.935 16 12 16s-1.892.232-2.676.754C8.561 17.263 8 18.057 8 19a1 1 0 0 0 1 1");
}

</style>
