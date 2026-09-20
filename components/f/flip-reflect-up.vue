<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vzhxywx4y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vzhxywx4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:flip-reflect-up" /></template>
