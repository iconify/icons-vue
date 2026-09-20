<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/q/qy80u1bjw.css';
import '../../css/f/fz451zb9n.css';
import '../../css/x/xcetmgeuw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGfM2vdeLS)"><path class="qy80u1bjw"/><path class="fz451zb9n"/></g><defs><clipPath id="SVGfM2vdeLS"><path class="xcetmgeuw"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:lodgify" /></template>
