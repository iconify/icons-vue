<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qlrm6yb-l.css';
import '../../css/n/n1mjunbsu.css';
import '../../css/h/h01tyzbfu.css';
import '../../css/g/gkm79o2wn.css';
import '../../css/f/f_qydnbny.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGKJaeveDz" class="qlrm6yb-l"/></defs><mask id="SVGYA3t2btq" class="n1mjunbsu"><use href="#SVGKJaeveDz"/></mask><g class="h01tyzbfu"><path class="gkm79o2wn"/><use href="#SVGKJaeveDz" mask="url(#SVGYA3t2btq)" class="f_qydnbny"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:copy-alt" /></template>
