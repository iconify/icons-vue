<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b15xjgb5x.css';
import '../../css/c/c50_lwbrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="b15xjgb5x"/><path class="c50_lwbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:anomaly-detection" /></template>
