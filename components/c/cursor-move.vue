<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k2yg8lbtx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k2yg8lbtx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber-color:cursor-move" /></template>
