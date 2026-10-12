<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mnmuv66eo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:flight-departure-sharp" /></template>
<style>
.mnmuv66eo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m17.34 5.58l-.43 1.59l-.16.58l-.45.4l-1.35 1.2l-.45.4l.15.58l1.45 5.59l.15.58l-.42.42l-.16.16l-.42.42l-.3-.52l-2.4-4.21l-.3-.52l-.42.42l-1.91 1.91l-.42.42v2.25l-.36.48l-.03.04l-.36.48l-.27-.54l-.96-1.92l-.27-.54l-.54-.27l-1.92-.96l-.54-.27l.48-.36l.04-.03l.48-.36H7.5l.42-.42l1.91-1.91l.42-.42l-.52-.3l-4.21-2.4l-.52-.3l.42-.42l.16-.16l.42-.42l.58.15l5.59 1.45l.58.15l.4-.45l1.2-1.35l.4-.45l.58-.16l1.59-.43l.58-.16zM3.75 20.75h16.5");
}

</style>
