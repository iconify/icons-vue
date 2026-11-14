<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p026xejwf"/><path class="gx7h9lllj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:camera-mode-dial" /></template>
<style>
.gx7h9lllj {
  d: path("M7.5 12a4.5 4.5 0 1 0 9 0a4.5 4.5 0 1 0-9 0ZM12 7.5V12");
}

.p026xejwf {
  d: path("m11.224 3.787l.213-1.27h1.126l.213 1.27l1.304.229l.634-1.12l1.059.385l-.234 1.266l1.146.662l.979-.836l.863.725l-.653 1.109l.851 1.014l1.206-.451l.563.976l-.993.82l.453 1.243l1.287-.011l.196 1.11l-1.214.43v1.324l1.214.43l-.196 1.11l-1.287-.011l-.453 1.243l.993.82l-.563.976l-1.206-.451l-.851 1.014l.653 1.109l-.863.725l-.979-.836l-1.146.662l.234 1.266l-1.059.385l-.634-1.12l-1.304.229l-.213 1.27h-1.126l-.213-1.27l-1.304-.229l-.634 1.12l-1.059-.385l.234-1.266l-1.146-.662l-.979.836l-.863-.725l.653-1.109l-.851-1.014l-1.206.451l-.563-.976l.993-.82l-.453-1.243l-1.287.011l-.196-1.11l1.214-.43v-1.324l-1.214-.43l.196-1.11l1.287.011l.453-1.243l-.993-.82l.563-.976l1.206.451l.851-1.014l-.653-1.109l.863-.725l.979.836l1.146-.662l-.234-1.266l1.059-.385l.634 1.12Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
