<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jtowsomii.css';
import '../../css/y/yqvkmow1r.css';
import '../../css/k/kfw3mq-ct.css';
import '../../css/z/zqtrx1b9w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="yqvkmow1r"/><path class="kfw3mq-ct"/><path class="zqtrx1b9w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:import" /></template>
