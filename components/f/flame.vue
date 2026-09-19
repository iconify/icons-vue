<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vp6swmwrc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vp6swmwrc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:flame" /></template>
