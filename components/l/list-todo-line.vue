<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9oz_-bvb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9oz_-bvb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:list-todo-line" /></template>
