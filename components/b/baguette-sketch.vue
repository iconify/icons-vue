<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/l/ljtayob0g.css';
import '../../css/q/q3ivf5tky.css';
import '../../css/y/yfb696n5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="ljtayob0g"/><path class="q3ivf5tky wm-k"/><path class="wm-a yfb696n5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:baguette-sketch" /></template>
