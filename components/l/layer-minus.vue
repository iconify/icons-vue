<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o4cfygela.css';
import '../../css/p/pxmikjbdi.css';
import '../../css/r/rykek3b0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="o4cfygela"/><path class="pxmikjbdi"/><path clip-rule="evenodd" class="rykek3b0h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs-poly:layer-minus" /></template>
