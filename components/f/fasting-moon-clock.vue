<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="yy17-hfii"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:fasting-moon-clock" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yy17-hfii {
  d: path("M17.069 12.044q.828-.359 1.568-.875T20 10q.057 1.117-.16 2.214m-7.78 7.187q-1.059.125-2.119-.002q-1.059-.127-2.059-.498q-.261-.097-.515-.21q-.255-.112-.502-.241q-.247-.128-.485-.271q-.239-.143-.468-.301q-.229-.157-.448-.329q-.219-.171-.427-.356t-.404-.382t-.38-.406t-.354-.429q-.171-.219-.327-.449q-.157-.23-.299-.47t-.269-.486q-.127-.248-.238-.503q-.112-.254-.207-.516q-.096-.261-.175-.528q-.079-.266-.142-.537t-.108-.546t-.074-.551t-.04-.554t-.006-.556t.028-.556t.063-.552t.097-.548t.13-.541t.163-.531t.196-.52q.107-.258.228-.508t.259-.492t.288-.475q.152-.233.318-.457q.166-.223.345-.436T4.5 4.25q.017.327.057.652q.041.325.105.646q.064.322.151.637q.088.316.198.625q.11.308.242.608t.286.589q.153.289.327.567t.368.541t.407.513q.212.25.443.483q.23.233.476.449q.247.215.508.413q.262.197.537.375q.275.177.562.334t.586.294q.298.136.605.25q.587.218 1.2.352q.612.134 1.237.183q.624.048 1.25.009t1.24-.164M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

</style>
