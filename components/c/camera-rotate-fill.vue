<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5cmkyb8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c5cmkyb8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:camera-rotate-fill" /></template>
