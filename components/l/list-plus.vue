<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/x/xe65wvb-d.css';
import '../../css/c/c3wgojkty.css';
import '../../css/y/yuobg4bux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="wm-k xe65wvb-d"/><path class="c3wgojkty wm-s"/><path class="wm-deco yuobg4bux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:list-plus" /></template>
