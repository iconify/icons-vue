<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-jx36qxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:houses" /></template>
<style>
.a-jx36qxx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 14.1566L12.7072 8.474C13.4532 7.842 14.5468 7.842 15.2928 8.474L22 14.1566M8 12.4621L8 19C8 20.1046 8.8954 21 10 21L18 21C19.1046 21 20 20.1046 20 19L20 12.4621M2 6.6149L5.7072 3.474C6.4532 2.842 7.5468 2.842 8.2928 3.474L10.363 5.2279M4 4.9204L4 10.6085M12 21L12 18C12 16.8954 12.8954 16 14 16C15.1046 16 16 16.8954 16 18L16 21");
}

</style>
