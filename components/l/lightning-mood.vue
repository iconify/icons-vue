<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="wlk5en25j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:lightning-mood" /></template>
<style>
.wlk5en25j {
  fill: var(--svg-color--fbb11c, #fbb11c);
  d: path("M43.4.159L12.06 28.492l24.31 7.538L18.12 64l35.26-33.426l-18.978-8.464z");
}

</style>
