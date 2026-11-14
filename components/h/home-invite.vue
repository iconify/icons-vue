<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="gq0-xvbim"/><path class="rf135ab2h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:home-invite" /></template>
<style>
.gq0-xvbim {
  d: path("M12.244 20.5H3.5v-10L12 3.25l8.5 7.25v1.656");
}

.rf135ab2h {
  d: path("M7.25 12a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM6 20.5c0-3 1.25-4 3-4s3 1 3 4m6-5.5v6m-3-3h6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
