<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yf4vd7pcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yf4vd7pcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:list-select" /></template>
