<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff2d-me7b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ff2d-me7b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:border-vertical" /></template>
