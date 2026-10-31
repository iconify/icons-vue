<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="jlh-1_mlw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:copy-select-20-regular" /></template>
<style>
.jlh-1_mlw {
  fill: currentColor;
  d: path("M7 7H5a2 2 0 0 0-2 2v6a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2h1a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3h2zm1.5 4c.276 0 .493.227.562.495A2 2 0 0 0 11 13h.75a.5.5 0 0 1 0 1H11a3 3 0 0 1-2.959-2.502c-.045-.272.183-.498.459-.498m9 0c.276 0 .505.226.459.498A3 3 0 0 1 15 14h-.75a.5.5 0 0 1 0-1H15c.934 0 1.718-.64 1.939-1.505c.068-.268.285-.495.561-.495m-9-4.5A.5.5 0 0 1 9 7v2a.5.5 0 0 1-1 0V7a.5.5 0 0 1 .5-.5m9 0a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-1 0V7a.5.5 0 0 1 .5-.5M11.75 2a.5.5 0 0 1 0 1H11a2 2 0 0 0-1.938 1.505C8.993 4.772 8.776 5 8.5 5s-.504-.226-.459-.498A3 3 0 0 1 11 2zM15 2a3 3 0 0 1 2.959 2.502c.046.272-.183.498-.459.498s-.493-.228-.561-.495A2 2 0 0 0 15 3h-.75a.5.5 0 0 1 0-1z");
}

</style>
