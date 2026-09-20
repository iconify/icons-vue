<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zeialtbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zeialtbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:code" /></template>
