<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ob0of34yq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:cup-soda-sharp" /></template>
<style>
.ob0of34yq {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 10H18M6 10C5.448 10 5 9.55 5 9C5 8.78 5.07 8.57 5.2 8.4L7 6H17L18.8 8.4C18.93 8.57 19 8.78 19 9C19 9.55 18.552 10 18 10M6 10L9 22H15L18 10M11 6L13 2H17");
}

</style>
