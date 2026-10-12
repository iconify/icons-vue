<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="owikbrb6w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:energy-label-sharp" /></template>
<style>
.owikbrb6w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.35 3h4.9l.42.42l.53.53l.43.43l-.43.42l-.53.53l-.42.42h-5.5V3zm0 5h6.9l.42.42l.53.53l.43.43l-.43.42l-.53.53l-.42.42h-7.5V8zm0 5h8.9l.42.42l.53.53l.43.43l-.43.42l-.53.53l-.42.42h-9.5V13zm0 5h10.9l.42.42l.53.53l.43.43l-.43.42l-.53.53l-.42.42H2.75V18zM14.8 8.87l1.65-1.49l.55-.5h4.25v5H17l-.55-.51l-1.65-1.49l-.55-.5z");
}

</style>
