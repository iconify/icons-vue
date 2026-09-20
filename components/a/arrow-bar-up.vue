<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbv05ubbo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tbv05ubbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:arrow-bar-up" /></template>
