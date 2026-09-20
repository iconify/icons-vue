<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zchtgcboh.css';
import '../../css/i/i1-lcibyb.css';
import '../../css/i/i5-w2mb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zchtgcboh"/><path class="i1-lcibyb"/><path class="i5-w2mb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-print" /></template>
