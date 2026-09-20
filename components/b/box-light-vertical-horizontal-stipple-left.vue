<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq6w5q5vp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="zq6w5q5vp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:box-light-vertical-horizontal-stipple-left" /></template>
