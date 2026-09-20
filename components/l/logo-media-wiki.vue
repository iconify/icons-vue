<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/njt4l8box.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g transform="translate(10 10)"><g id="SVGNMsnceQG"><path id="SVG18Gx1iGl" class="njt4l8box"/><use href="#SVG18Gx1iGl" transform="rotate(15)"/><use href="#SVG18Gx1iGl" transform="rotate(30)"/><use href="#SVG18Gx1iGl" transform="rotate(45)"/><use href="#SVG18Gx1iGl" transform="rotate(60)"/><use href="#SVG18Gx1iGl" transform="rotate(75)"/></g><use href="#SVGNMsnceQG" transform="rotate(90)"/><use href="#SVGNMsnceQG" transform="rotate(180)"/><use href="#SVGNMsnceQG" transform="rotate(270)"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ooui:logo-media-wiki" /></template>
