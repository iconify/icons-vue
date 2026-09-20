<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci7gq9rvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ci7gq9rvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:camera-2-ai-fill" /></template>
