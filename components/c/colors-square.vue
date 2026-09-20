<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/s/s1yet0cyf.css';
import '../../css/d/di-sq0b4x.css';
import '../../css/l/lylwz-bed.css';
import '../../css/r/rvymobzlx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="s1yet0cyf"/><path class="di-sq0b4x"/><path class="lylwz-bed"/><path class="rvymobzlx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:colors-square" /></template>
