<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/m/m45ig3bmy.css';
import '../../css/x/xjhwnvbgl.css';
import '../../css/y/yh5ahcbjw.css';
import '../../css/j/japg61bou.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="m45ig3bmy"/><path class="xjhwnvbgl"/><path clip-rule="evenodd" class="yh5ahcbjw"/><path class="japg61bou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:apple-bold" /></template>
