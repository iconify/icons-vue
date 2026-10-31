<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vmy6o3vyt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vmy6o3vyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bulb-sparkle-fill-round" /></template>
