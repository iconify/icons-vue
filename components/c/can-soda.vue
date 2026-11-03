<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nv4rw0b6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:can-soda" /></template>
<style>
.nv4rw0b6i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 7L16.6 10.4667C16.8596 10.8129 17 11.2339 17 11.6667L17 19.1716C17 19.702 16.7893 20.2107 16.4142 20.5858L15.5858 21.4142C15.2107 21.7893 14.702 22 14.1716 22L9.8284 22C9.298 22 8.7893 21.7893 8.4142 21.4142L7.5858 20.5858C7.2107 20.2107 7 19.702 7 19.1716L7 11.6667C7 11.2339 7.1404 10.8129 7.4 10.4667L10 7M17 7L7 7M16 2L13 7");
}

</style>
