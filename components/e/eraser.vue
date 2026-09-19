<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zeid6ab-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":667,"height":672};
const content = `<path class="zeid6ab-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:eraser" /></template>
