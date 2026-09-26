<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t29jepb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:heading-3-fill" /></template>
<style>
.t29jepb1q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 4V20M11 4V20M2 12H11M17 13H21L18.8564 16C20.0403 16 21 16.8954 21 18C21 19.1046 20.0403 20 18.8564 20C18.0906 20 17.3829 19.6188 17 19");
}

</style>
