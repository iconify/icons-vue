<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/g/gyp90cb4j.css';
import '../../css/w/w2vappbii.css';
import '../../css/y/yu9sii_3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="gyp90cb4j"/><path class="w2vappbii wm-a"/><path class="wm-s yu9sii_3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:christmas-candle" /></template>
