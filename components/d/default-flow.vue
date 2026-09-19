<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g_kxo3vjf.css';
import '../../css/y/ycj4854jp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":2048};
const content = `<path class="g_kxo3vjf"/><path transform="matrix(125.07186 0 0 96.75291 2539.419 -100217.58)" class="ycj4854jp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bpmn:default-flow" /></template>
