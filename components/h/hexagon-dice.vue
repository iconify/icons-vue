<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddvgu8bvv.css';
import '../../css/s/s_ho3ac6o.css';
import '../../css/u/uybgto0ku.css';
import '../../css/t/trcn_rbat.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ddvgu8bvv"><path class="s_ho3ac6o"/><path class="uybgto0ku"/><path class="trcn_rbat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:hexagon-dice" /></template>
