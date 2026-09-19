<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="fmf6wp8tz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:eject-button" /></template>
<style>
.fmf6wp8tz {
  fill: currentColor;
  d: path("M53.214 10.787c-11.715-11.716-30.711-11.716-42.426 0c-11.717 11.715-11.717 30.711 0 42.426c11.715 11.716 30.711 11.716 42.426 0s11.715-30.711 0-42.426M48 43.351H16V37.65h32zm-32-9.702l16-19l16 19z");
}

</style>
