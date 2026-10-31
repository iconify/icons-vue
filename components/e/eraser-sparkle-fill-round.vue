<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/puznxsb5b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="puznxsb5b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:eraser-sparkle-fill-round" /></template>
