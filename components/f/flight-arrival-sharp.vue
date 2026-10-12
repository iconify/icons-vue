<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u73jx__4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flight-arrival-sharp" /></template>
<style>
.u73jx__4l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.92 15.84l-1.59-.43l-.58-.16l-.4-.45l-1.2-1.35l-.4-.45l-.58.15l-5.59 1.45l-.58.15l-.42-.42l-.16-.16l-.42-.42l.52-.3l4.21-2.4l.52-.3l-.42-.42l-1.91-1.91L7.5 8H5.25l-.48-.36l-.04-.03l-.48-.36l.54-.27l1.92-.96l.54-.27l.27-.54l.96-1.92l.27-.54l.36.48l.03.04l.36.48V6l.42.42l1.91 1.91l.42.42l.3-.52l2.4-4.21l.3-.52l.42.42l.16.16l.42.42l-.15.58l-1.45 5.59l-.15.58l.45.4l1.35 1.2l.45.4l.16.58l.43 1.59l.16.58zM3.75 20.75h16.5");
}

</style>
