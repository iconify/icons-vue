<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/x/xw-o2-_kb.css';
import '../../css/j/ju-zdhbkf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="xw-o2-_kb"/><path class="ju-zdhbkf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:hammer-outline" /></template>
