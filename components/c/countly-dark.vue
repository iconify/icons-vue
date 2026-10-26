<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckn5liu4w.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fjmqa0b9f.css';
import '../../css/f/fvnsj1qgk.css';
import '../../css/w/wqhpa-e9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":280,"height":87};
const content = `<mask id="SVGIYlLQbvL" width="77" height="77" x="6" y="5" maskUnits="userSpaceOnUse" style="mask-type:alpha"><path class="ckn5liu4w"/></mask><g class="ft5dv1b6b"><path class="fjmqa0b9f"/><g mask="url(#SVGIYlLQbvL)"><path class="fvnsj1qgk"/><path clip-rule="evenodd" class="wqhpa-e9f"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:countly-dark" /></template>
