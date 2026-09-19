<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/d7w95cbsp.css';
import '../../css/n/n4mhsebtw.css';
import '../../css/d/d5g8zobgk.css';
import '../../css/w/w2-dmlbzr.css';
import '../../css/y/yvtk3obra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="d7w95cbsp"/><mask id="SVGcFaS5cXn" width="32" height="24" x="0" y="0" maskUnits="userSpaceOnUse" style="mask-type:luminance"><path clip-rule="evenodd" class="n4mhsebtw"/></mask><g mask="url(#SVGcFaS5cXn)"><path class="d5g8zobgk"/><path clip-rule="evenodd" class="w2-dmlbzr"/><path clip-rule="evenodd" class="yvtk3obra"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flagpack:kp" /></template>
