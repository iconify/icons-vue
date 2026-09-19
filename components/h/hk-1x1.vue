<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ktj_s9fwf.css';
import '../../css/l/l_k5w5_ge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ktj_s9fwf"/><path id="SVGg6HuSbAj" class="l_k5w5_ge"/><use href="#SVGg6HuSbAj" transform="rotate(72 248.5 259.5)"/><use href="#SVGg6HuSbAj" transform="rotate(144 248.5 259.5)"/><use href="#SVGg6HuSbAj" transform="rotate(216 248.5 259.5)"/><use href="#SVGg6HuSbAj" transform="rotate(288 248.5 259.5)"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flag:hk-1x1" /></template>
