<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/j/j3_4id34h.css';
import '../../css/g/gd92vsrsz.css';
import '../../css/r/rq8v8obdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path class="j3_4id34h"/><path clip-rule="evenodd" class="gd92vsrsz"/><path class="rq8v8obdh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:images-bold" /></template>
