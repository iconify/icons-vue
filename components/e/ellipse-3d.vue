<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/f/fmlnzirud.css';
import '../../css/f/fh5p1wbcf.css';
import '../../css/w/wjl0m-b2p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="fmlnzirud"/><path class="fh5p1wbcf"/><path class="wjl0m-b2p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:ellipse-3d" /></template>
