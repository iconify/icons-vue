<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i26fpsbxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i26fpsbxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent-emoji-flat:chess-pawn" /></template>
