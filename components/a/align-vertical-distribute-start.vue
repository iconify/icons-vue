<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xi0wn1ibg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:align-vertical-distribute-start" /></template>
<style>
.xi0wn1ibg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M22 4H2M22 14H2M16 8V6C16 4.895 15.1046 4 14 4H10C8.8954 4 8 4.895 8 6V8C8 9.105 8.8954 10 10 10H14C15.1046 10 16 9.105 16 8ZM18 14H6C4.8954 14 4 14.895 4 16V18C4 19.105 4.8954 20 6 20H18C19.1046 20 20 19.105 20 18V16C20 14.895 19.1046 14 18 14Z");
}

</style>
