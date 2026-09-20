<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/h/hc3ha90ri.css';
import '../../css/k/kxln91b_t.css';
import '../../css/d/d1s63ybjv.css';
import '../../css/g/g622mc63x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="hc3ha90ri"/><path class="kxln91b_t"/><circle class="d1s63ybjv"/><path class="g622mc63x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:half-dotted-circle-play-filled" /></template>
