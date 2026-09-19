<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ikuyx85cg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ikuyx85cg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="game-icons:combination-lock" /></template>
