<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aq6z8si9v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:guidepoint-arrow-up-sharp" /></template>
<style>
.aq6z8si9v {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16 17C16 15.34 17.343 14 19 14C20.657 14 22 15.34 22 17C22 18.66 20.657 20 19 20C17.343 20 16 18.66 16 17ZM16 17H8M8 17C8 18.66 6.657 20 5 20C3.343 20 2 18.66 2 17C2 15.34 3.343 14 5 14C6.657 14 8 15.34 8 17ZM7.513 10L12 4L16.487 10H7.513Z");
}

</style>
