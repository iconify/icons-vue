<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/f/fcdm4-b9o.css';
import '../../css/t/t6lndlu0r.css';
import '../../css/o/ol5--vb1y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="fcdm4-b9o"/><path class="t6lndlu0r"/><path clip-rule="evenodd" class="ol5--vb1y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:image-up" /></template>
