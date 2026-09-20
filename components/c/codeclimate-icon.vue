<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":142};
const content = `<path class="m0gno_blt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:codeclimate-icon" /></template>
<style>
.m0gno_blt {
  fill: var(--svg-color--2b2b2b, #2b2b2b);
  d: path("m84.841 28.3l28.773 28.772l28.772 29.51l27.297 27.296l-28.772 28.035l-27.297-26.559L84.84 86.582l-8.115 6.64l-36.887 37.625l-11.067 11.066L0 113.878l10.329-12.541zM171.16 0L256 84.104l-28.772 29.51l-56.07-56.07l-19.919 19.92l-28.772-28.772z");
}

</style>
