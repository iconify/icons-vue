<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ogaeq8urq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-left-right-2-sharp" /></template>
<style>
.ogaeq8urq {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M1 17L2 17L12.2604 17L12.9144 17M7.8062 11.7061L8.1053 12L13.1934 17L8.1053 22L7.8062 22.2939M23 7L22 7L11.7396 7L11.0856 7M16.1938 12.2939L15.8947 12L10.8066 7L15.8947 2L16.1938 1.7061");
}

</style>
