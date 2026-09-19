<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="b76psvbae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:downwards-button" /></template>
<style>
.b76psvbae {
  fill: currentColor;
  d: path("M53.212 10.785c-11.715-11.714-30.711-11.714-42.426 0c-11.715 11.717-11.715 30.711 0 42.427s30.711 11.717 42.426 0c11.717-11.716 11.717-30.71 0-42.427M31.999 47l-20-20h40z");
}

</style>
