<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/y/yfsl5absb.css';
import '../../css/k/k11donbcg.css';
import '../../css/w/wl3zckjly.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yfsl5absb"/><path clip-rule="evenodd" class="k11donbcg"/><path class="wl3zckjly"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:banknote2-duotone" /></template>
