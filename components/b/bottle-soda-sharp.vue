<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sanier0dl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bottle-soda-sharp" /></template>
<style>
.sanier0dl {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 4L8.5 5C8.5 6.5 11 7 11 9.5L11 12C11 13 10 13.5 10 14.5C10 15.5 11 16 11 17L11 22L3 22L3 17C3 16 4 15.5 4 14.5C4 13.5 3 13 3 12L3 9.5C3 7 5.5 6.5 5.5 5L5.5 4M20.9995 10.0698L18.5 10L14.9091 10L16 22L20 22ZM18.5 10L20 6.5L20.2597 5.8939M5 4L5 2L9 2L9 4Z");
}

</style>
