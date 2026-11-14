<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ibausvdgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:human-rights-law" /></template>
<style>
.ibausvdgg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 3.5v17m-2 0h2.9M5 3.5h12M2 8l3-4.5L8 8a3 3 0 0 1-6 0Zm14.145 2.876q-.115-.035-.227-.078t-.221-.096q-.108-.052-.212-.113q-.104-.06-.202-.129t-.192-.145q-.092-.077-.179-.161q-.086-.083-.165-.174t-.152-.186q-.072-.097-.135-.198t-.12-.209q-.056-.106-.103-.217t-.084-.225q-.038-.114-.067-.231q-.028-.117-.048-.235q-.019-.119-.028-.239T14 8l3-4.5L20 8q0 .187-.023.373q-.023.185-.07.367q-.046.181-.114.355t-.158.339t-.198.316t-.237.289q-.127.137-.27.258q-.143.12-.3.222M16.25 15a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0Zm-1.75 6.75c0-1.25 1.5-2.25 3.5-2.25s3.5 1 3.5 2.25");
}

</style>
