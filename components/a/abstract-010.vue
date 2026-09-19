<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xz0__bbtl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xz0__bbtl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-010" /></template>
