<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ai2u7s5kj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ai2u7s5kj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:abstract-020" /></template>
