<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="w90w9lbzl"/><path class="tej51lbtb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:can-soda-duotone" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tej51lbtb {
  d: path("M17 7L7 7M16 2L13 7");
}

.w90w9lbzl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.8 6.4L17.4001 9.8668C17.7895 10.3861 18 11.0176 18 11.6667L18 19.1716C18 19.9672 17.6839 20.7303 17.1213 21.2929L16.2929 22.1213C15.7303 22.6839 14.9672 23 14.1716 23L9.8284 23C9.0328 23 8.2697 22.6839 7.7071 22.1213L6.8787 21.2929C6.3161 20.7303 6 19.9672 6 19.1716L6 11.6667C6 11.0176 6.2105 10.386 6.6 9.8667L9.2 6.4C9.3889 6.1482 9.6852 6 10 6L14 6C14.3148 6 14.6111 6.1482 14.8 6.4Z");
  stroke: none;
}

</style>
