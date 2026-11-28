<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmgi9rbzh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmgi9rbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:flame" /></template>
