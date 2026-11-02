<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="yndr5_bwa"/><path class="ssmnx9b-z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:dog-duotone-round" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.ssmnx9b-z {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 5h8c.7-.7 1.8-1 3-1c1.5 0 2 1.5 2 3v4c0 1.6-.8 3-2 3l-3 5c-.6 1-1.4 2-3 2h-2c-1.6 0-2.4-1-3-2l-3-5c-1.2 0-2-1.4-2-3V7c0-1.5.5-3 2-3c1.2 0 2.3.3 3 1m0 0c-.7 3-1.5 6.5-3 9m11-9c.7 3 1.5 6.5 3 9m-9-3h.01M14 11h.01M10 14h4l-2 2Zm2 2v2");
}

.yndr5_bwa {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M8.377 4h7.246c.948-.746 2.194-1 3.377-1c1.061 0 1.924.53 2.437 1.452C21.866 5.225 22 6.126 22 7v4c0 1.326-.471 2.847-1.642 3.598c-.229.149-.482.26-.747.327l-2.754 4.589c-.368.614-.797 1.199-1.362 1.646c-.72.568-1.582.84-2.495.84h-2c-.913 0-1.775-.272-2.495-.84c-.565-.447-.994-1.032-1.362-1.646l-2.754-4.589a2.5 2.5 0 0 1-.747-.327C2.471 13.847 2 12.326 2 11V7c0-.874.134-1.775.563-2.548C3.076 3.53 3.939 3 5 3c1.183 0 2.429.254 3.377 1");
}

</style>
