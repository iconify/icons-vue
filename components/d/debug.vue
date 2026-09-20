<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vk_1_t7py.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vk_1_t7py"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:debug" /></template>
