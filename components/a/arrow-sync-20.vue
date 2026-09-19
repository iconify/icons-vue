<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pni936bua.css';
import '../../css/n/newr62bds.css';
import '../../css/d/d3eqnjbjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGJZgUOdCP)" clip-rule="evenodd" class="pni936bua"/><defs><linearGradient id="SVGJZgUOdCP" x1="14" x2="6" y1="16.5" y2="0" gradientUnits="userSpaceOnUse"><stop class="newr62bds"/><stop offset="1" class="d3eqnjbjz"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-color:arrow-sync-20" /></template>
