<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="js7sv8zrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:flag-off-sharp" /></template>
<style>
.js7sv8zrt {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 14C5.2311 14.6566 6.6048 15 8 15C9.3952 15 10.7689 14.6566 12 14C12.4514 13.7593 12.9219 13.5606 13.4056 13.4056M4 4L4 23M18.4215 13.291L19.341 13.6841C19.5646 13.7797 19.7845 13.8851 20 14L20 3C18.7689 2.3434 17.3952 2 16 2C14.6048 2 13.2311 2.3434 12 3C11.2202 3.4159 10.3833 3.7061 9.5199 3.863L8.536 4.0418M1.7071 1.7071L22.2929 22.2929");
}

</style>
