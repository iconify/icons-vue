<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_h8f0b4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:certificate-seal-sharp" /></template>
<style>
.h_h8f0b4q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.25 10.54V2.75H3.75v16.5h7.15a6.5 6.5 0 0 1 5.35-8.71ZM7 7h6m-6 3.5h3m7.4 3.05l.39.29l.4.3l.49.07l.48.07l.49.07l.07.49l.07.48l.07.49l.3.4l.29.39l.3.4l-.3.4l-.29.39l-.3.4l-.07.49l-.07.48l-.07.49l-.49.07l-.48.07l-.49.07l-.4.3l-.39.29l-.4.3l-.4-.3l-.39-.29l-.4-.3l-.49-.07l-.48-.07l-.49-.07l-.07-.49l-.07-.48l-.07-.49l-.3-.4l-.29-.39l-.3-.4l.3-.4l.29-.39l.3-.4l.07-.49l.07-.48l.07-.49l.49-.07l.48-.07l.49-.07l.4-.3l.39-.29l.4-.3z");
}

</style>
