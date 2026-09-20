<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d4o3cmuso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d4o3cmuso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:icomoon" /></template>
