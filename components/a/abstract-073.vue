<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zf6ahbb-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zf6ahbb-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-073" /></template>
