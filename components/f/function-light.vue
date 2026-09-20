<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="pyr7p9bes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:function-light" /></template>
<style>
.pyr7p9bes {
  fill: currentColor;
  d: path("M206 40a6 6 0 0 1-6 6h-29.29a26 26 0 0 0-25.58 21.35L135.19 122H184a6 6 0 0 1 0 12h-51l-10.33 56.8A38 38 0 0 1 85.29 222H56a6 6 0 0 1 0-12h29.29a26 26 0 0 0 25.58-21.35l9.94-54.65H72a6 6 0 0 1 0-12h51l10.33-56.8A38 38 0 0 1 170.71 34H200a6 6 0 0 1 6 6");
}

</style>
