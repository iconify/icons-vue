<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/b/bouczrbwq.css';
import '../../css/q/qgoj2cb0j.css';
import '../../css/h/hd8ymvble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="bouczrbwq"/><path class="qgoj2cb0j"/><path class="hd8ymvble"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:ai-video" /></template>
