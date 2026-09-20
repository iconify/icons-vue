<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtmswccww.css';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rjmt1lb2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVGRHCYbejF" class="mtmswccww"/></defs><g class="cuyn6tgcc"><path class="rjmt1lb2s"/><use href="#SVGRHCYbejF"/><use href="#SVGRHCYbejF"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:devices2-filled" /></template>
