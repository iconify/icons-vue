<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cr3ansb8s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:explosion-sharp-duotone" /></template>
<style>
.cr3ansb8s {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.096 2.0006L12.8828 8.3435L19.3293 4.972L16.3187 9.7966L21.9976 10.4729L16.2933 12.789L20.7205 16.247L15.0232 15.7367L14.774 21.9984L11.7033 16.1841L8.2472 21.4589L7.9805 15.6988L2.0018 15.6212L7.3698 12.0596L2.3693 8.9814L8.6766 8.4088Z");
}

</style>
