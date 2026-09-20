<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j3nskzbyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j3nskzbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:drawing-board-fill" /></template>
