<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wmw7d9hmc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:blind-hiring" /></template>
<style>
.wmw7d9hmc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.129 11.806q.193.308.424.589t.495.531t.557.465t.612.391t.656.31t.69.225t.713.137t.724.046t.724-.046t.712-.136t.69-.225t.656-.311q.318-.175.611-.39q.293-.214.557-.464t.495-.53t.424-.589m-.8-7.122q-.2-.2-.418-.379q-.219-.18-.454-.337t-.484-.291t-.51-.241q-.262-.109-.532-.191q-.271-.082-.548-.137t-.559-.083T12 3t-.563.028t-.557.082q-.277.055-.547.137t-.53.189q-.261.108-.51.241t-.483.289q-.235.157-.453.336q-.219.178-.418.378M4 20.25c0-2 3.6-3.25 8-3.25s8 1.25 8 3.25c0 .65-.4 1.25-1 1.25H5c-.6 0-1-.6-1-1.25ZM5.25 7.5h13.5V9H5.25Z");
}

</style>
