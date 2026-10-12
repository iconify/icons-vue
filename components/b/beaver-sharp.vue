<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="soisy5bfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:beaver-sharp" /></template>
<style>
.soisy5bfc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 3.5h1.66l1.24.62a1.6 1.6 0 1 1 2.15 1.89l.15.35l.1.7l1.89 1.323l-.44 1.937c-.25 1.54-2 2.42-4.25 2.42h.5v2.51H9v-2.51h.5c-2.25 0-4-.88-4.25-2.42l-.44-1.937L6.7 7.06l.1-.7l.15-.35A1.6 1.6 0 1 1 9.1 4.12l1.24-.62zM9.75 6.75h0m4.5 0h0m-3.25 3h2M12 12v3.25m-6.5 3h13v3h-13z");
}

</style>
