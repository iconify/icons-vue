<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pcz7ahuni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:crosshair-x-sharp" /></template>
<style>
.pcz7ahuni {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M20 12C20 16.4183 16.4183 20 12 20C7.5817 20 4 16.4183 4 12C4 7.5817 7.5817 4 12 4C16.4183 4 20 7.5817 20 12ZM12 1L12 7M12 23L12 17M1 12L7 12M23 12L17 12M9.2071 9.2071L14.7929 14.7929M14.7929 9.2071L9.2071 14.7929");
}

</style>
