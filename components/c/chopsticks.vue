<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez_6ovbaq.css';
import '../../css/h/hrzob008l.css';
import '../../css/i/ij2x_72vy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<defs><path id="SVGaTGCleZN" class="ez_6ovbaq"/></defs><use href="#SVGaTGCleZN" class="hrzob008l"/><use href="#SVGaTGCleZN" class="ij2x_72vy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:chopsticks" /></template>
