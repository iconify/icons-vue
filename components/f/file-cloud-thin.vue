<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="iq9-4-b9y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:file-cloud-thin" /></template>
<style>
.iq9-4-b9y {
  fill: currentColor;
  d: path("m210.83 85.17l-56-56A4 4 0 0 0 152 28H56a12 12 0 0 0-12 12v88a4 4 0 0 0 8 0V40a4 4 0 0 1 4-4h92v52a4 4 0 0 0 4 4h52v124a4 4 0 0 1-4 4h-24a4 4 0 0 0 0 8h24a12 12 0 0 0 12-12V88a4 4 0 0 0-1.17-2.83M156 41.65L198.34 84H156ZM108 132a47.72 47.72 0 0 0-45.3 32H60a32 32 0 0 0 0 64h48a48 48 0 0 0 0-96m0 88H60a24 24 0 0 1 0-48h.66c-.2 1.2-.35 2.41-.46 3.64a4 4 0 0 0 8 .72a41 41 0 0 1 1.23-6.92a5 5 0 0 0 .21-.73A40 40 0 1 1 108 220");
}

</style>
