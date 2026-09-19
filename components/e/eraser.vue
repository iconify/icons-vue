<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pue5zmbks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pue5zmbks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:eraser" /></template>
