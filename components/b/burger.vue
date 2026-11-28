<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/b6ra2rkgs.css';
import '../../css/h/hyfvbjbmz.css';
import '../../css/x/xh7fozb3j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="b6ra2rkgs"/><path class="hyfvbjbmz"/><path class="xh7fozb3j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:burger" /></template>
