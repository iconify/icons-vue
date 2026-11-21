<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xoe34z4ce"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chef-hat-sharp" /></template>
<style>
.xoe34z4ce {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 18.5L6 11.9357C3.7 11.4714 2 9.6143 2 7.5714C2 4.9714 4.2 2.9286 7 2.9286C7.6 2.9286 8.1 3.0214 8.6 3.2071C9.4 2.4643 10.6 2 12 2C13.4 2 14.6 2.4643 15.4 3.2071C15.9 3.0214 16.4 2.9286 17 2.9286C19.8 2.9286 22 4.9714 22 7.5714C22 9.6143 20.3 11.4714 18 11.9357L18 18.5M6 17L18 17L18 22L6 22Z");
}

</style>
