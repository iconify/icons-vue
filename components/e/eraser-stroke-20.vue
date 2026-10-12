<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv8044bua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="iv8044bua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:eraser-stroke-20" /></template>
