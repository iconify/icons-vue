<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/r/rp-rncc0y.css';
import '../../css/m/mt58vcclw.css';
import '../../css/h/h_mjq-bfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rp-rncc0y"/><path class="mt58vcclw"/><path clip-rule="evenodd" class="h_mjq-bfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:draw-compass-filled" /></template>
