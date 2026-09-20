<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c4qnjpezl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c4qnjpezl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:arrow-big-up" /></template>
