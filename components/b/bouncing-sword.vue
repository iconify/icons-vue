<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxnef9jnz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yxnef9jnz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:bouncing-sword" /></template>
