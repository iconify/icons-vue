<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7415bc3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:layers-merge-sharp" /></template>
<style>
.b7415bc3e {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 1L12 13M7.7071 8.7071L12 13L16.2929 8.7071M1.4819 11.7151L12 17.5L22.5181 11.7151M1.4819 16.2151L12 22L22.5181 16.2151");
}

</style>
