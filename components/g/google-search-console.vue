<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hxh9xub-j.css';
import '../../css/j/juiwqcb2u.css';
import '../../css/n/nncmxpb2n.css';
import '../../css/b/bucyfy22j.css';
import '../../css/i/i72psgb8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":40,"height":40};
const content = `<g class="cuyn6tgcc"><g clip-path="url(#SVGbZii27FA)"><path class="hxh9xub-j"/><path class="juiwqcb2u"/><path class="nncmxpb2n"/><path class="bucyfy22j"/></g><defs><clipPath id="SVGbZii27FA"><path class="i72psgb8a"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:google-search-console" /></template>
