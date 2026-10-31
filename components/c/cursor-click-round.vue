<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ke5v90e9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ke5v90e9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cursor-click-round" /></template>
