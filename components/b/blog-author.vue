<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ymol7lb7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:blog-author" /></template>
<style>
.ymol7lb7t {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.75 7q0-1.968 1.391-3.359T10.5 2.25t3.359 1.391T15.25 7t-1.391 3.359T10.5 11.75t-3.359-1.391T5.75 7m9.054 9.868l1.744-1.745q-.129-.102-.266-.2q-2.32-1.673-5.782-1.673t-5.782 1.673Q2.25 16.702 2.25 19.5q0 1.75 1.75 1.75h9.78q-.632-1.006-.137-2.243l.386-.963q.266-.667.775-1.176m6.726-2.398q1.28 1.28 0 2.56l-3.282 3.283q-.327.326-.755.497l-.965.386q-.812.325-1.431-.293q-.618-.619-.293-1.432l.385-.963q.172-.429.499-.756l3.282-3.282q1.28-1.28 2.56 0m-1.06 1.06q-.22-.219-.44 0l-3.282 3.282q-.108.109-.165.252l-.236.589l.588-.235q.144-.058.253-.167l3.282-3.281q.219-.22 0-.44");
}

</style>
