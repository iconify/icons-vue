<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="qtrer_ikg"/><path class="viw75zb6q"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:can-soda-sharp-duotone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qtrer_ikg {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.8 6.4L17.4 9.8667L17.8 10.4001C17.9298 10.5732 18 10.7838 18 11.0001L18 20C18 20.2652 17.8946 20.5196 17.7071 20.7071L15.7071 22.7071C15.5196 22.8946 15.2652 23 15 23L9 23C8.7348 23 8.4804 22.8946 8.2929 22.7071L6.2929 20.7071C6.1054 20.5196 6 20.2652 6 20L6 11.0001C6 10.7838 6.0702 10.5732 6.2 10.4001L6.6 9.8667L9.2 6.4C9.3889 6.1482 9.6852 6 10 6L14 6C14.3148 6 14.6111 6.1482 14.8 6.4Z");
  stroke: none;
}

.viw75zb6q {
  d: path("M18 7L6 7M16.2913 1.5145L13 7");
}

</style>
