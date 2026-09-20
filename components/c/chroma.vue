<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qbqmwsb_x.css';
import '../../css/f/ft5dv1b6b.css';
import '../../css/d/dery1ly2w.css';
import '../../css/i/iis4squhf.css';
import '../../css/z/z_bj0tbab.css';
import '../../css/p/p7ibcdbtv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":53,"height":40};
const content = `<mask id="SVGFRkwMdWh" width="53" height="36" x="0" y="2" maskUnits="userSpaceOnUse" style="mask-type:luminance"><path class="qbqmwsb_x"/></mask><g mask="url(#SVGFRkwMdWh)" class="ft5dv1b6b"><path class="dery1ly2w"/><path class="iis4squhf"/><path class="z_bj0tbab"/><path class="p7ibcdbtv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:chroma" /></template>
