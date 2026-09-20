<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ype8rpb3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:down-left-arrow" /></template>
<style>
.ype8rpb3p {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("m29.82 98.25l8.28-53.74l14.18 14.18l28.94-28.94l16.96 16.97l-28.94 28.93l14.32 14.33z");
}

</style>
