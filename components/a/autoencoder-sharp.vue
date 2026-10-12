<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kb9z25b5z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:autoencoder-sharp" /></template>
<style>
.kb9z25b5z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.56 3.84l4.88 3.57l.81.59v8l-.81.59l-4.88 3.57l-.81.59V3.25zm17.69.41v16.5l-.81-.59l-4.88-3.57l-.81-.59V8l.81-.59l4.88-3.57l.81-.59zM12 10v4");
}

</style>
