<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ydcvy7b8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ydcvy7b8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:folder-open-fill" /></template>
