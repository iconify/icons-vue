<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs93ev7th.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs93ev7th"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:information-fill" /></template>
