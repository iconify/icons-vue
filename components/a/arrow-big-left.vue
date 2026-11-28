<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6yti7l8q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6yti7l8q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:arrow-big-left" /></template>
