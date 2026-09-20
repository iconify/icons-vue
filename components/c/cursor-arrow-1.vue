<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxxtszp8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxxtszp8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:cursor-arrow-1" /></template>
