<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="thlw7vb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-up-wide-narrow-sharp" /></template>
<style>
.thlw7vb4m {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 19L6 6M1.7071 10.2929L6 6L10.2929 10.2929M13 6L23 6M13 10L21 10M13 14L19 14M13 18L17 18");
}

</style>
