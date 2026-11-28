<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq8x4zxcz.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zn0h9p04f.css';
import '../../css/z/zbwamwa-z.css';
import '../../css/q/qjzyurbpi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gq8x4zxcz secondary"/><g class="dt0cm9dhy primary"><path class="zn0h9p04f"/><path class="zbwamwa-z"/><path class="qjzyurbpi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:camera-off-duo" /></template>
