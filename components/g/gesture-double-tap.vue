<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdk6ubcvg.css';
import '../../css/k/kdupjtxcu.css';
import '../../css/y/yxss69ubf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vdk6ubcvg"/><path class="kdupjtxcu"/><path class="yxss69ubf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:gesture-double-tap" /></template>
