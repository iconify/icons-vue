<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pp6t5hhfe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:game-trigger-right-sharp" /></template>
<style>
.pp6t5hhfe {
  fill: currentColor;
  d: path("M2 20V8q0-1.65 1.175-2.825T6 4h12q1.65 0 2.825 1.175T22 8v12zm4.35-4.5h1.375v-2.55h.925l1.825 2.55H12.1l-2.05-2.725q.7-.275 1.063-.787t.362-1.263q0-1.125-.65-1.675t-2-.55H6.35zm1.4-3.575V9.7h1.125q.65 0 .938.288t.287.812q0 .55-.337.838t-.913.287zM14.5 15.5h1.375V9.75H18V8.5h-5.6v1.25h2.1z");
}

</style>
