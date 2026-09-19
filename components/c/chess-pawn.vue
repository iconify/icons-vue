<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cf3sejcfw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="cf3sejcfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-high-contrast:chess-pawn" /></template>
