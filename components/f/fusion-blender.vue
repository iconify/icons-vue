<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zkmovacmh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zkmovacmh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:fusion-blender" /></template>
