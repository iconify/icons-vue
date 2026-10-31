<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7wu9kboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7wu9kboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:list-minus-fill-round" /></template>
