<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/w/w672jk75d.css';
import '../../css/r/r60q05bdu.css';
import '../../css/u/u10o49kya.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="w672jk75d"/><path class="r60q05bdu"/><path class="u10o49kya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:align-top-bold" /></template>
