<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7gj44blj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":180,"height":180};
const content = `<path class="g7gj44blj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:flame" /></template>
