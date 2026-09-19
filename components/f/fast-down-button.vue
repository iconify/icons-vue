<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="dsvm5n1ip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:fast-down-button" /></template>
<style>
.dsvm5n1ip {
  fill: currentColor;
  d: path("M53.213 10.787c-11.715-11.715-30.711-11.715-42.426 0c-11.716 11.717-11.716 30.711 0 42.426s30.711 11.715 42.426 0s11.716-30.71 0-42.426M50 32.723L32 51.998L14 32.723h11.879L14 20h36L38.121 32.723z");
}

</style>
