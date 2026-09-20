<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="xgp-m39ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:envelope-open-bold" /></template>
<style>
.xgp-m39ig {
  fill: currentColor;
  d: path("m230.66 86l-96-64a12 12 0 0 0-13.32 0l-96 64A12 12 0 0 0 20 96v104a20 20 0 0 0 20 20h176a20 20 0 0 0 20-20V96a12 12 0 0 0-5.34-10M89.81 152L44 184.31v-65Zm24.55 12h27.28L187 196H69.05Zm51.83-12L212 119.29v65ZM128 46.42l74.86 49.91L141.61 140h-27.22L53.14 96.33Z");
}

</style>
