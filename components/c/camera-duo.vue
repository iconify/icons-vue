<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq8x4zxcz.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/x/xdgjxabpg.css';
import '../../css/v/vzxf1fubx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gq8x4zxcz secondary"/><g class="dt0cm9dhy primary"><path class="xdgjxabpg"/><path class="vzxf1fubx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:camera-duo" /></template>
