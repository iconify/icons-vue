<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rvohuybli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:fast-reverse-button" /></template>
<style>
.rvohuybli {
  fill: currentColor;
  d: path("M53.212 10.787c-11.715-11.715-30.711-11.715-42.426 0c-11.715 11.717-11.715 30.712 0 42.427s30.711 11.715 42.426 0c11.717-11.715 11.717-30.71 0-42.427m-8.213 39.212L32.276 38.122v11.877L12.999 32.001L32.276 14v11.879L44.999 14z");
}

</style>
