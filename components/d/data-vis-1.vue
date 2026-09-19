<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yp2o07q1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="yp2o07q1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:data-vis-1" /></template>
