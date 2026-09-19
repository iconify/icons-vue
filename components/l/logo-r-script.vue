<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gjw-j4bpy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gjw-j4bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:logo-r-script" /></template>
