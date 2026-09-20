<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kcehd9pft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:fast-up-button" /></template>
<style>
.kcehd9pft {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M98.99 121.76L67.28 66.84h31.71L64 6.24l-34.99 60.6h31.71l-31.71 54.92z");
}

</style>
