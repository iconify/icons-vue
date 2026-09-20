<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="kh3gm-bli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:codepen-logo-fill" /></template>
<style>
.kh3gm-bli {
  fill: currentColor;
  d: path("m235.79 89l-104-56a8 8 0 0 0-7.58 0l-104 56A8 8 0 0 0 16 96v64a8 8 0 0 0 4.21 7l93.89 50.6a4 4 0 0 0 5.9-3.52v-57.3L66.55 128L32 146.61v-37.22L66.55 128l16.88-9.09L40.87 96L120 53.39v45.83l-36.57 19.69l44.57 24l44.57-24l16.88 9.09L224 109.39v37.22L189.45 128L136 156.78v57.3a4 4 0 0 0 5.9 3.52l93.89-50.6a8 8 0 0 0 4.21-7V96a8 8 0 0 0-4.21-7m-63.22 30L136 99.22V53.39L215.13 96Z");
}

</style>
