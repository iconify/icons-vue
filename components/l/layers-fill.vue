<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nousg6kcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:layers-fill" /></template>
<style>
.nousg6kcq {
  fill: currentColor;
  d: path("m7.553 5.106l4-2a1 1 0 0 1 .894 0l8 4a.998.998 0 0 1 0 1.788l-8 4a1 1 0 0 1-.894 0l-8-4a.998.998 0 0 1 0-1.788ZM12 14.882l7.553-3.776a1 1 0 1 1 .894 1.788l-8 4a1 1 0 0 1-.894 0l-8-4a1 1 0 1 1 .894-1.788Zm0 4l7.553-3.776a1 1 0 1 1 .894 1.788l-8 4a1 1 0 0 1-.894 0l-8-4a1 1 0 1 1 .894-1.788Z");
}

</style>
