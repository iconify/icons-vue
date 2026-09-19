<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/nr175gb2k.css';
import '../../css/q/qjvk9obmc.css';
import '../../css/o/o5713nbxf.css';
import '../../css/m/mnd7z85kz.css';
import '../../css/w/w315w0b1j.css';
import '../../css/k/k7uplq85b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="nr175gb2k"/><path class="qjvk9obmc"/><path clip-rule="evenodd" class="o5713nbxf"/><path class="mnd7z85kz"/><path clip-rule="evenodd" class="w315w0b1j"/><path class="k7uplq85b"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:hand-holding-seedling" /></template>
