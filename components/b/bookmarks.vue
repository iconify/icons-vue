<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mpk8h1bxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mpk8h1bxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:bookmarks" /></template>
