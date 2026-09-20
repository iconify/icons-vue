<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fjebheb9k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-2};
const content = `<path class="fjebheb9k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:bookmark-minus" /></template>
