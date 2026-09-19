<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3dpzbtra.css';
import '../../css/z/zhcnnrbqz.css';
import '../../css/y/yg0-h_7ex.css';
import '../../css/x/xk7n9ubji.css';
import '../../css/y/yhtph-bed.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y3dpzbtra"><path class="zhcnnrbqz"/><path class="yg0-h_7ex"/><path class="xk7n9ubji"/><path class="yhtph-bed"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:arena" /></template>
