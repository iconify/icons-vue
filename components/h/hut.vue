<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j7ha0-b_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j7ha0-b_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:hut" /></template>
