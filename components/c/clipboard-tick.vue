<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/l/lnc4c1gzh.css';
import '../../css/z/zsivi9bzc.css';
import '../../css/d/d3-3v1nvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="lnc4c1gzh"/><path class="zsivi9bzc"/><path class="d3-3v1nvx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:clipboard-tick" /></template>
