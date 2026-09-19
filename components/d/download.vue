<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbo6mfjnh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbo6mfjnh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:download" /></template>
