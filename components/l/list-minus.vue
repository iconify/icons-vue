<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/y/yl7a92tqe.css';
import '../../css/o/okp7pp4nk.css';
import '../../css/y/yuobg4bux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="wm-k yl7a92tqe"/><path class="okp7pp4nk wm-s"/><path class="wm-deco yuobg4bux"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:list-minus" /></template>
