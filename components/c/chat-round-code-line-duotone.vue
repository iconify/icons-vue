<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="snto2-zvc"/><path class="wg8azcbhn"/><path class="hyjgutf1e"/><path class="f0g-urbji"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:chat-round-code-line-duotone" /></template>
<style>
.f0g-urbji {
  d: path("M8.4997 9L8.32813 9.17157C6.99479 10.5049 6.32812 11.1716 6.32812 12C6.32812 12.8284 6.99479 13.4951 8.32813 14.8284L8.4997 15");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.hyjgutf1e {
  d: path("M13.2939 7.16992L11.9998 11.9996L10.7058 16.8292");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.snto2-zvc {
  d: path("M22 12C22 17.5228 17.5228 22 12 22C10.4003 22 8.88837 21.6244 7.54753 20.9565C7.19121 20.7791 6.78393 20.72 6.39939 20.8229L4.17335 21.4185C3.20701 21.677 2.32295 20.793 2.58151 19.8267L3.17712 17.6006C3.28001 17.2161 3.22094 16.8088 3.04346 16.4525C2.37562 15.1116 2 13.5997 2 12C2 6.47715 6.47715 2 12 2C17.5228 2 22 6.47715 22 12Z");
}

.wg8azcbhn {
  d: path("M15.5 9L15.6716 9.17157C17.0049 10.5049 17.6716 11.1716 17.6716 12C17.6716 12.8284 17.0049 13.4951 15.6716 14.8284L15.5 15");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
