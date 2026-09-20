<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zy_3vkbzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zy_3vkbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:flip-rotate-clockwise" /></template>
