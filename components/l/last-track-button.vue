<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="nsy3b5b7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:last-track-button" /></template>
<style>
.nsy3b5b7o {
  fill: currentColor;
  d: path("M10.787 53.213c11.715 11.717 30.711 11.717 42.426 0c11.716-11.715 11.716-30.711 0-42.426s-30.711-11.715-42.426 0s-11.716 30.711 0 42.426M12 18h5.219v14l17.39-14v14L52 18v28L34.608 32v14l-17.39-14v14H12z");
}

</style>
