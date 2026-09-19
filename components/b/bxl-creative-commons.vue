<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzpap0btc.css';
import '../../css/y/ydu5kibqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzpap0btc"/><path class="ydu5kibqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-creative-commons" /></template>
