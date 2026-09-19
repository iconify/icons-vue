<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxzx2mk3k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="zxzx2mk3k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-110" /></template>
