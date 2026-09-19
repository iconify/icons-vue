<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cuyn6tgcc.css';
import '../../css/c/c6rglys6g.css';
import '../../css/c/c7ywoacuf.css';
import '../../css/u/uip_4ybxi.css';
import '../../css/m/m2nzsorih.css';
import '../../css/n/nqwui_bjj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="c6rglys6g"/><path clip-rule="evenodd" class="c7ywoacuf"/><path class="uip_4ybxi"/><path class="m2nzsorih"/><path class="nqwui_bjj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:coctail" /></template>
