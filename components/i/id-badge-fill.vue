<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jsii2p_js"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:id-badge-fill" /></template>
<style>
.jsii2p_js {
  fill: currentColor;
  d: path("M4 5a3 3 0 0 1 3-3h10a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3Zm6 0a1 1 0 0 0 0 2h4a1 1 0 0 0 0-2Zm-1 7a3 3 0 1 0 6 0a3 3 0 0 0-6 0m0 8h6a1 1 0 0 0 1-1c0-.943-.561-1.737-1.324-2.246C13.892 16.232 12.935 16 12 16s-1.892.232-2.676.754C8.561 17.263 8 18.057 8 19a1 1 0 0 0 1 1");
}

</style>
