<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc-vztb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tc-vztb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:compass" /></template>
