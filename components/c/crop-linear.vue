<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/x/xoi8enb4l.css';
import '../../css/d/dux539s4k.css';
import '../../css/z/zl063ub9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="xoi8enb4l"/><path class="dux539s4k"/><path class="zl063ub9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:crop-linear" /></template>
