<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/p/p2vd3xbgk.css';
import '../../css/t/tiqb603qs.css';
import '../../css/w/wrgkn9b6i.css';
import '../../css/l/l2tlt6_ly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="p2vd3xbgk"/><path class="tiqb603qs"/><path class="wrgkn9b6i"/><path class="l2tlt6_ly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pencil:cloud-up" /></template>
