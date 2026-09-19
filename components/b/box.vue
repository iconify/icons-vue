<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u0ruh7b8j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u0ruh7b8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:box" /></template>
