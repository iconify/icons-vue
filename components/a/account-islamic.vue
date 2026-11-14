<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="xlhq3iy4l"/><path class="ihwc2vaqo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:account-islamic" /></template>
<style>
.ihwc2vaqo {
  d: path("M19.5 15.25a3.25 3.25 0 1 0 0 5.5a3 3 0 0 1 0-5.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xlhq3iy4l {
  d: path("M12.8 21.5H4.5v-19h15v9.6m-11-9.6v19m3-14.5h4");
}

</style>
