<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j1_g_if2b.css';
import '../../css/h/hntgybcog.css';
import '../../css/c/cpnkntywn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGezrOSaGs" class="j1_g_if2b"/></defs><g class="hntgybcog"><path class="cpnkntywn"/><use href="#SVGezrOSaGs"/><use href="#SVGezrOSaGs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:frame5" /></template>
