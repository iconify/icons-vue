<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yf6vs7ttm.css';
import '../../css/w/woyg9ybfc.css';
import '../../css/h/hul4uub1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yf6vs7ttm"/><path class="woyg9ybfc"/><path class="hul4uub1l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:anchor" /></template>
