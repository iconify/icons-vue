<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymbg1h5wp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:home-play" /></template>
<style>
.ymbg1h5wp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.2928 3.47L20.2928 9.4C20.7414 9.78 21 10.34 21 10.93V19C21 20.1 20.1046 21 19 21H5C3.8954 21 3 20.1 3 19V10.93C3 10.34 3.2586 9.78 3.7072 9.4L10.7072 3.47C11.4532 2.84 12.5468 2.84 13.2928 3.47Z");
}

</style>
