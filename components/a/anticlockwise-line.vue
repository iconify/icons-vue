<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zr0zv381u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zr0zv381u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:anticlockwise-line" /></template>
