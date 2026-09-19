<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s26yy7bfo.css';
import '../../css/h/hpiehn9em.css';
import '../../css/a/adgytybhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path fill="url(#SVGWy8Dkdne)" class="s26yy7bfo"/><defs><linearGradient id="SVGWy8Dkdne" x1="527.926" x2="527.926" y1="275" y2="421.221" gradientTransform="translate(-311.724 -183.75)scale(.7117)" gradientUnits="userSpaceOnUse"><stop class="hpiehn9em"/><stop offset="1" class="adgytybhn"/></linearGradient></defs>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:githubcopilot" /></template>
